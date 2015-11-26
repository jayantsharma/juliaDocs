## Examples
---
#### Read from a file
```julia
julia> fp = open("foo");
julia> print(readall(fp))
"bar"
```

#### Append to a file
```julia
julia> fp = open("foo","a");
julia> str = "baz";
julia> write(fp, str);
julia> close(fp);
julia> readall("foo")
"barbaz"
```

#### Repeat first line
```julia
julia> function f(file)
            arr = readlines(file)
            str = arr[1]
            write(file, str)
        end
f (generic function with 1 method)
julia> open(f, "numbers", "r+");    # file contains 1,2,3 in successive lines
julia> readall("numbers")
"1\n2\n3\n1\n"
```

