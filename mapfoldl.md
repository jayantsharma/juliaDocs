## Examples
---
```julia
julia> mapfoldl((x) -> x+1, -, -1, [5:7])	# = ((((-1) - 6) - 7) - 8)
-22
```
