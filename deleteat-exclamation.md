## Examples
---
```julia
julia> foo = [6, 5, 4, 3, 2, 1];

julia> deleteat!(foo, 5);

julia> foo
5-element Array{Int64,1}:
 6
 5
 4
 3
 1

julia> deleteat!(foo, 2:2:5);		# sorted and unique itr

julia> foo
3-element Array{Int64,1}:
 6
 4
 1
```
