# Reading 2

[What is a Port Scanner and How Does it Work?](https://www.varonis.com/blog/port-scanning-techniques)

1. What is a port? Describe it with an analogy that would help a family member understand.

A port is a virtual location where networking communication starts and ends.  I would say it's like a mailbox, that unless you have the mailbox open and accessible, no letters will be able to get delivered (received) or go out (picked up by carrier).

2. What does a port scanner send to a port to check the current status?

A port scanner sends network request to a port to check the current status.

3. When a port scanner sends a request to connect, what are the three possible responses? Describe them.

The three possible responses are open/accepted, closed/not listening, and filtered/dropped/blocked.  If open/accepted, then the port is fully functioning.  If closed and not listening then the port is in use at that moment.  If filtered/dropped/blocked, then there will be no response.

4. What is the difference between TCP and UDP?

TCP is transmission control protocol which sends packets in order with a process to confirm each packet is successful (three way handshake, error checking, and verification).  UDP is faster but has no error checking, good for streaming and gaming as it is a connectionless protocol that just sends packets with no guarantee that they'll be received.

[Common Ports](https://www.professormesser.com/network-plus/n10-008/n10-008-video/common-ports-n10-008/)


List and describe the ports used for the following:
Telnet - TCP Port 23 (telecommunication network protocol)
SSH - TCP Port 22 (Secure Shell)
DNS - UDP/TCP Port 53 (Domain Name System)
SMTP - TCP Port 25, TCP Port 587 (Simple Mail Transfer Protocol)
HTTP - TCP Port 80 (Hypertext Transfer Protocol)
HTTPS - TCP Port 443 (Hypertext Transfer Protocol Secure)
RDP - TCP Port 3389 (Remote Desktop Protocol)
Ping - "A a ping test uses ICMP, so there are no real ports being used. ICMP basically roofs, or sits on top of, the IP address. Therefore it is not a layer four protocol. That means that you don't have to worry about assigning ports to a ping test."
Source: https://www.colocationamerica.com/how-does-ping-work


## Things I want to know more about

All of it!
