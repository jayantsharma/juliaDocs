## Examples
---
```julia
julia> dict = {"A"=>1, "B"=>2, "C"=>3, "D"=>4};
julia> foo = keys(dict);
julia> for key in foo
		println(string(key,".."));
	end;
B..
A..
C..
D..
```
