## Examples
---
```julia
julia> foo = [6, 5, 4, 3, 2, 1]; splice!(foo, 5)
2

julia> foo
5-element Array{Int64,1}:
 6
 5
 4
 3
 1

julia> splice!(foo, 5, -1)
1

julia> foo
5-element Array{Int64,1}:
  6
  5
  4
  3
 -1

julia> splice!(foo, 1, [-1, -2, -3])
6

julia> foo
7-element Array{Int64,1}:
 -1
 -2
 -3
  5
  4
  3
 -1

julia> splice!(foo, 4:3, 2)	# insert 2 before index 4
0-element Array{Int64,1}

julia> foo
8-element Array{Int64,1}:
 -1
 -2
 -3
  2
  5
  4
  3
 -1
```
