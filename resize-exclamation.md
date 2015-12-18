## Examples
---
```julia
julia> foo = [6, 5, 4, 3, 2, 1];

julia> resize!(foo, 3);	foo
3-element Array{Int64,1}:
 6
 5
 4

julia> resize!(foo, 5); foo
5-element Array{Int64,1}:
 6
 5
 4
 0
 0
```
