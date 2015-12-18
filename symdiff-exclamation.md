## Examples
---
```julia
julia> a = IntSet([1:2:10]);

julia> symdiff!(a,6);
julia> a
IntSet([1, 3, 5, 6, 7, 9])

julia> symdiff!(a,[6:10]);
julia> a
IntSet([1, 3, 5, 8, 10])

julia> b = IntSet([0:2:10]);
julia> symdiff!(a, b);
julia> a
IntSet([0, 1, 2, 3, 4, 5, 6])
```
