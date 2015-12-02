## Examples
---
```julia
julia> foo = [-1, -2, -3];
julia> setindex!(foo, 2, 2)
3-element Array{Int64,1}:
-1
2
-3

julia> bar = zeros(2, 2);           # 2x2 array of zeros
julia> setindex!(bar, 42, 2, 1)
2x2 Array{Float64,2}:
0.0   0.0
42.0  0.0
```