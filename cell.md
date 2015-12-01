## Examples
---
```julia
julia> cell(3)
3-element Array{Any,1}:
#undef
#undef
#undef
julia> cell((2,2))      # equivalent to cell(2, 2)
2x2 Array{Any,2}:
#undef  #undef
#undef  #undef
```