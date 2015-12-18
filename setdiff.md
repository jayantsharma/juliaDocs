## Examples
---
```julia
julia> all = [10:-1:1];
julia> odd = [1:2:10];

julia> even = setdiff(all, odd)		# note the ordering of elements in result
5-element Array{Int64,1}:
 10
  8
  6
  4
  2
```
