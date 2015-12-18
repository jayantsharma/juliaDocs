## Examples
---
```julia
julia> a = Set("Hello")
Set{Char}({'e','H','l','o'})

julia> b = Set([10:-1:6])
Set{Int64}({7,9,10,8,6})

julia> union(a,b)
Set{Integer}({7,9,10,'e','H','l',8,'o',6})
```
