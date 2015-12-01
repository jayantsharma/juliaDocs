## Examples
---
```julia
julia> eye(2)
2x2 Array{Float64,2}:
 1.0    0.0
 0.0    1.0
julia> eye(2,3)
2x3 Array{Float64,2}:
 1.0    0.0    0.0
 0.0    1.0    0.0
julia> foo = zeros((2,2));
julia> eye(foo)
2x2 Array{Float64,2}:
 1.0    0.0
 0.0    1.0
 ```