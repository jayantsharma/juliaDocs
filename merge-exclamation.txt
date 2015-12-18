## Examples
---
```julia
julia> a = Dict("foo" => 0.0, "bar" => 42.0)
Dict{ASCIIString,Float64} with 2 entries:
  "bar" => 42.0
  "foo" => 0.0

julia> b = Dict(utf8("baz") => 17, utf8("bar") => 4711)
Dict{UTF8String,Int64} with 2 entries:
  "bar" => 4711
  "baz" => 17

julia> merge!(a, b);

julia> a
Dict{UTF8String,Float64} with 3 entries:
  "bar" => 4711.0
  "baz" => 17.0
  "foo" => 0.0
```
