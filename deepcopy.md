## Examples
---
```julia
julia> foo = [1,2,3];
julia> dict = {"a"=>foo};
julia> bar = copy(dict)
Dict{Any,Any} with 1 entry:
    "a" => [1,2,3]
julia> baz = deepcopy(dict)
Dict{Any,Any} with 1 entry:
    "a" => [1,2,3]
julia> foo[1] = 42;
julia> bar
Dict{Any,Any} with 1 entry:
    "a" => [42,2,3]
julia> baz
Dict{Any,Any} with 1 entry:
    "a" => [1,2,3]
```