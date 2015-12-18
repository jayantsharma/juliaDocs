## Examples
---
```julia
julia> foo = [[1:3] [4:6]]
3x2 Array{Int64,2}:
 1  4
 2  5
 3  6

julia> collect(foo)
6-element Array{Int64,1}:
 1
 2
 3
 4
 5
 6
 
julia> dict = {"a" => 1, "b" => 10};

julia> collect(dict)
2-element Array{(Any,Any),1}:
 ("b",10)
 ("a",1)
```	
