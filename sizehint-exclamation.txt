## Examples
---
```julia
julia> foo = Dict();

julia> sizehint!(foo, 10000);

julia> for i in [1:10000]
		foo[string(i)] = 2*i;
	end;
```
