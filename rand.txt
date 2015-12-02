## Examples
---
```julia
julia> rand()
0.41545291085770697
julia> rand(Uint32)
0x96d887ee
julia> rand(3)
3-element Array{Float64,1}:
 0.806615
 0.974651
 0.380263
julia> rand(Int8,2,2)
2x2 Array{Int8,2}:
 -54    107
 -1     -100
 julia> rand(0:10)
 5
 julia> rand(0:2:20, 4)
 4-element Array{Int64,1}:
  2
  10
  20
  6
```
