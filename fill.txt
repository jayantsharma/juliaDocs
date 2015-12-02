## Examples
---
```julia
julia> fill(3, 1)
1-element Array{Int64,1}:
 3
 ```
 #### Referencing another collection
 ```julia
 julia> foo = [1,2];
 julia> bar = fill(foo, 1, 2)
 1x2 Array{Array{Int64,1},2}:
  [1,2]     [1,2]
 julia> foo[1] = 42;
 julia> bar
 1x2 Array{Array{Int64,1},2}:
 [42,2]     [42,2]
```
#### Using functions
```julia
julia> function Foo()
                    4^3
            end;
julia> fill(Foo(), 1)
1-element Array{Int64,1}:
 64
```