## Examples
---
```julia
julia> foo = [1,2,4,8];
julia> state = start(foo);
julia> while !done(foo, state)
            (i, state) = next(foo, state)
            println(i*i)
        end                 # semantics of a for loop
1
4
16
64
```