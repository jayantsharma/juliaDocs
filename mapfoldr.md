## Examples
---
```julia
julia> mapfoldr((x) -> x+1, -, -1, [5:7])	                   # = (6 - (7 - (8 - (-1))))
8
```
