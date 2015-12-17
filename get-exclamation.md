## Examples
---
```julia
julia> dict = {"A"=>1, "B"=>2};
julia> get!(dict,"A",42)
1
julia> get!(dict,"C",42)
42
julia> 	get!(dict,"D") do		# equivalent to get!(100, dict, "D");
		return 100
	end;
julia> dict
Dict{Any,Any} with 4 entries:
 "B" => 2
 "A" => 1
 "C" => 42
 "D" => 100
```
