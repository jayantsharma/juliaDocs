## Examples
---
```julia
julia> foo = trues(2,2)
2x2 BitArray{2}:
 true   true
 true   true
julia> convert(Int8, foo[1][1])
1
```