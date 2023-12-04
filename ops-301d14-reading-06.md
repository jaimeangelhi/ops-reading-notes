# Reading 6

1. What is the main purpose for implementing NAT on a network?

Basically it's to allow multiple devices to connect to the internet by a single ip address.

"Network Address Translation (NAT) is a process in which one or more local IP address is translated into one or more Global IP address and vice versa in order to provide Internet access to the local hosts. Also, it does the translation of port numbers i.e. masks the port number of the host with another port number, in the packet that will be routed to the destination. It then makes the corresponding entries of IP address and port number in the NAT table. NAT generally operates on a router or firewall."



2. At what layer of the OSI model does NAT happen?

Layer 3, Network

3. What happens to packets when NAT runs out of addresses in the pool of available IPs?

If no address is left in the pool configured then the packets will be dropped and an Internet Control Message Protocol (ICMP) host unreachable packet to the destination is sent. 

4.What disadvantage does using NAT pose for routers?

Translation makes delays while switching paths, certain functions don't work when NAT enabled, IPSec gets more complicated (and other tunneling protocols), "Also, the router being a network layer device, should not tamper with port numbers(transport layer) but it has to do so because of NAT."

## Things I want to know more about

How is this best utilized.
