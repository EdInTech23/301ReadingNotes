# Reading
## For Lecture & Lab
### What is a Port Scanner and How Does it Work?

### What is a port? Describe it with an analogy that would help a family member understand.
Ports are virtual places within an operating system where network connections start and end. They help computers sort the network traffic they receive.

### What does a port scanner send to a port to check the current status?
 What a port scanner does is send a packet of network data to a port to check the current status.

### When a port scanner sends a request to connect, what are the three possible responses? Describe them.
1. Open, Accepted: The computer responds and asks if there is anything it can do for you.
2. Closed, Not Listening: The computer responds that “This port is currently in use and unavailable at this time.”
3. Filtered, Dropped, Blocked: The computer doesn’t even bother to respond.

### What is the difference between TCP and UDP?
TCP  uses 3way handshake, sends packets in order and checks for errors 
UDP does not check for errors and some times if you miss a packet youll never get it. but it is faster becuase it doesnt do all that TCP does
Common Ports
### List and describe the ports used for the following:
1. Telnet: 
2. SSH TCP/22
3. DNS TCP/53
4. SMTP TCP/25 (PLAINTEXT) TCP/587
5. HTTP 80
6. HTTPS 443
8. RDP 3389
9. Ping
