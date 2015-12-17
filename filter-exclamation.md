## Examples
---
```julia
julia> foo = [1:5];
julia> function isOdd(x)
		x % 2 != 0
       end

julia> filter!(isOdd, foo);
julia> foo
3-element Array{Int64,1}:
 1
 3
 5
```
