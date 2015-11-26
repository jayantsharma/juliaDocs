## Examples
***
```julia
julia> fp = open("foo", "w");           # empty file
julia> fp = write(fp, "The answer is 42.\n");
julia> flush(fp);
julia> close(fp);
```