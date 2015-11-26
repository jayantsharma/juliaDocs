## Examples
---
```julia
julia> foo = readline();
abc
julia> print(foo);
"abc\n"
```

### Reading from a file
```julia
julia> fp = open("helloworld.txt");    
julia> readline(fp)     # read first line
"hello\n"
julia> readline(fp)     # read second line
"world\n"
```