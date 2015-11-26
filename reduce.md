## Examples
---
```julia
julia> reduce(*, [1,2,3,4,5])       
120
julia> reduce(+, 10, [1,2,3,4,5])   
25
```

#### Reducing using a function
```julia
julia>  function foo (x,y)
            x+y+2
        end
julia> reduce(foo, 10, [1,2,3,4,5])
35
```