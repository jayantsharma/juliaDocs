## Examples
---
```julia
julia> foo = [1:3];

julia> issubset(foo, [1:10])
true

julia> issubset(foo, [1:2])
false

julia> issubset(foo, [3:-1:1])
true
```
