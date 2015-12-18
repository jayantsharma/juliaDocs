## Examples
---
```
julia> foo = [1 2 3; 4 5 6]
2x3 Array{Int64,2}:
 1  2  3
 4  5  6
 
julia> last(foo)
6

julia> last([-1:-2:-10])
-9

julia> last(1:2:0)	# empty range
0
```
