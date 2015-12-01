## Examples
---
```julia
julia> foo = [-3, -2, -1];
julia> getindex(foo, 2);
-2
julia> str = "Hello";
julia> getindex(str, 1);
'H'
julia> getindex(str, 6);
ERROR: BoundsError()
```
