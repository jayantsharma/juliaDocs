## Examples
---
```julia
julia> foo = IntSet([1:125]);
julia> bar = complement(foo);

julia> for i in bar
		if(i <= 128)
			println(i);
		else
			break;
		end
	end
0
126
127
128
```