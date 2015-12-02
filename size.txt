## Examples
---
```julia
julia> foo = [1,2,3];
julia> size(foo)
(3,)
julia> bar = Array(Int8, 3, 4);
julia> size(bar)
(3,4)
julia> size(bar, 1)
3
```