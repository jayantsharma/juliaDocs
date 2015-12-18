## Examples
---
```julia
julia> dict = {"A"=>1, "B"=>2, "C"=>3, "D"=>4};
julia> bar = collect(values(dict))	               # convert from ValueIterator to Array
4-element Array{Any,1}:
 2
 1
 3
 4
 
julia> reduce(*,bar)			# 2 * 1 * 3 * 4
24

julia> foldr(-,bar)			# (2 - (1 - (3 - 4)))
0
```
