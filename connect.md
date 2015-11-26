## Examples
---
### A simple Echo server
```julia
julia> @async begin
         server = listen(2001)
         while true
           sock = accept(server)
           @async while isopen(sock)
             write(sock,readline(sock))
           end
         end
       end
Task

julia> clientside=connect(2001)
TCPSocket(open, 0 bytes waiting)

julia> @async while true
          write(STDOUT,readline(clientside))    # prepare to listen
       end

julia> println(clientside,"Hello World from the Echo Server")

julia> Hello World from the Echo Server

julia> close(clientside)    #disconnect
```

