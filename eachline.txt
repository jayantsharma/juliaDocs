## Examples
---
### Iterate over a file's contents
```
julia> fp = open("numbers.txt");
julia> iter = eachline(fp);
julia> for i in iter
            print(i)
        end
1
2
3
4
5
julia> close(fp)