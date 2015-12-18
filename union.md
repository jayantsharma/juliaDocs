## Examples
---
```julia
julia> a = Set("Hello")
Set{Char}({'e','H','l','o'})

julia> b = Set([10:-1:6])
IntSet([6,7,8,9,10])

julia> union(a,b)
9-element Array{Int64,1}:
 101
  72
 108
 111
   6
   7
   8
   9
  10
```
