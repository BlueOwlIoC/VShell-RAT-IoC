VShell is a RAT coded in Go. Following are the features of VShell:-

1. **Characterestics**
   
Support C2 of ebpf client (demo video: https://www.bilibili.com/video/BV1Vw411t78a)
Perfect interactive virtual terminal
No compilation environment is required, the server directly generates the client
No special operating environment is required, a single file is run on the server
Support Windows shellcode client
Ultra-fast proxy function
Supports the memory to run plug-ins in multiple formats (exe, .net, elf, dll, so, dylib)
Support WebSocket CDN transfer
Clients that support forward and reverse connections
Support agent online and agent chain

2. **Traffic**

Support TCP, UDP/KCP, WebSocket, DNS, DOH, DOT protocols

The WebSocket protocol supports the use of CDN transit

Communications are encrypted using a custom salt by default

3. **Management functions**

1.File management
2. Interactive virtual terminal, Linux, MacOS, and Windows all support interaction
3. Screenshot
4. Custom plug-in operation
5. Add boot startup
6.NPS agent


4. **The server directly generates the client**

You can use the server to directly generate the client. The client does not require any parameters or configuration files to run.

The client supports four types, and the web page contains instructions for use.

Stager reverse client
Stagerless reverse client
forward client
ebpf forward client

5.**NPS proxy function**

Supports all existing proxy functions of NPS, just set the proxy directly on the WEB side

This project is found in: https://github.com/veo/vshell
