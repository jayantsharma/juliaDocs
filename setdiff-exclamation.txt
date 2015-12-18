## Examples
---
```julia
julia> s1 = Set("Hello");
julia> s2 = Set("Hello World");

julia> setdiff!(s2, s1);

julia> s2
Set{Char}({'d',' ','r','W'})
```
