## Examples
---
```julia
julia> server = listen(2000)    # Listens on localhost:2000 (IPv4)
TcpServer(active)

julia> server = listen(ip"::1",2000)     # Listens on localhost:2000 (IPv6)
TCPServer(active)

julia> server = listen(IPv4(0),2001)     # Listens on port 2001 on all IPv4 interfaces
TCPServer(active)

julia> listen("testsocket")     # Listens on a domain socket/named pipe
PipeServer(active)
```