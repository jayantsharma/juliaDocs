## Examples
---
### A simple TCP server
```
julia> @async begin
         server = listen(2000)
         while true
           sock = accept(server)
           println("Hello World")
         end
       end
Task (waiting) @0x000000000023286b0

julia> client = connect(2000);
Hello World

julia> close(client)
```