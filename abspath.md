## abspath(path::String) -> String
---
abspath(path::String)

Convert a **path** to an absolute path by adding the current directory if necessary.

## Examples
---
```julia
julia> abspath("Downloads")
"/home/johnDoe/Downloads"
julia> abspath("/root")
"/root"
julia> abspath("..")
"/home/"