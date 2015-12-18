## Examples
---
```julia
julia> dict = ["A"=>1, "B"=>2];

julia> get(dict, "A", 42)
1

julia> get(dict, "C", 42)
42

julia> get(() -> "Hello", dict, "D")
"Hello"
```
#### `do` block syntax
```julia
julia> function f(key)
		get(dict,key) do		# dict from above
			reduce(+,[1:10])	# = 1 + 2 + 3 ..
		end
	end;					    
julia> f("B")
2
julia> f("foo")
55
```
