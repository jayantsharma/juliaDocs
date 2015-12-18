## Examples
---
```julia
julia> a = IntSet([0:2:20]);	# table of 2

julia> b = IntSet([0:3:30]);	# table of 3

julia> intersect!(a, b);
julia> a
IntSet([0,6,12,18])
```
