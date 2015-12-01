## Examples
---
```julia
julia> foo = [1,2,3];
julia> similar(foo, Int8, 3, 3)
3x3 Array{Int8,2}:
 -112   -101    0
 19     -30     0
 124    127     64
```