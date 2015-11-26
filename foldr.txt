## Examples
---
```julia
julia> foldr(string, " world", ["h","e","l","l","o"])   # string("a","b") = "ab"
"hello world"
julia> foldr(-, [1,5,15])
11