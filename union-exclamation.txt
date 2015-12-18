## Examples
---
```julia
julia> s = Set();

julia> union!(s, [1:5]);

julia> union!(s, [-5:2:0]);

julia> s
Set{Any}({4,-3,-1,2,3,-5,5,1})
```
