## Examples
---
```julia
julia> foo = falses(1,2)
1x2 BitArray{2}:
 false   false
julia> convert(Int8, foo[1][1])
0
```