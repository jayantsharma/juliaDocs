## Examples
---
```julia
julia> dict = {"A"=>1, "B"=>2, "C"=>3, "D"=>4};
julia> pop!(dict,"A")
1
julia> pop!(dict,"E")
ERROR: key not found: "E"
 in pop! at dict.jl:646
julia> pop!(dict,"E",42)
42
julia> dict
Dict{Any,Any} with 3 entries:
 "B" => 2
 "C" => 3
 "D" => 4
```
