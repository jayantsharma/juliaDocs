## Examples
---
```julia
julia> foo = IntSet([5:100]);
julia> m = maximum(foo);	# = 100

julia> complement!(foo);

julia> for i in foo
		if(i <= m)
			println(i);
		else
			break;
		end
	end
0
1
2
3
4
```