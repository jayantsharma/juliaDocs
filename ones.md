## Examples
---
```julia
julia> ones(Float16, (2,2))
2x2 Array{Float16,2}:
 1.0    1.0
 1.0    1.0
julia> foo = zeros(Int8, 2);
julia> ones(foo)
2-element Array{Int8,1}:
 1
 1
```