## Examples
---
```julia
julia> file = open("foo", "w");     # create file, if doesn't exist
julia> write(fp, "Hi there!")
9
julia> close(fp);
julia> readall(fp)
"Hi there!"
julia> # write(fp, "Hi ", "there!") 
julia> # write(fp, "Hi ") + write(fp, "there!")
julia> # are also valid.
```