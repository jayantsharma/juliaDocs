## Examples
---
### Read lines from a file
```
fp = open("numbers.txt");
foo = readlines(fp)     # can be a socket stream too, for example
5-element Array{Union(ASCIIString,UTF8String),1}:
"1\n"
"2\n"
"3\n"
"4\n"
"5\n"
```