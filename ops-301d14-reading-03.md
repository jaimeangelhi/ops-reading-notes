# Reading 3

[CIDR Block Notation Explained in 2 Minutes](https://medium.com/@acropoiesis/cidr-block-notation-explained-in-2-minutes-1010ec0dbc15)

1. What is CIDR notation? a CIDR block?

CIDR notation represents a CIDR block which is just a range of IP addresses.

2. How many octets are found in an IPv4 address?

An IPv4 address has 4 octets that add up to 32 bits.

3. Setting binary aside and using the decimal system, what is the range of numbers found in an octet?

The range of numbers found in an octet is 0.0.0.0 - 255.255.255.255.

4. What does the final digit after the “/” represent in an IPv4 address?

The final digit after the "/" in an IPv4 address is how many bits make up the mask.

5. How many IP addresses are in the CIDR block 10.0.0.0/24?

In a CIDR (Classless Inter-Domain Routing) notation like "10.0.0.0/24," the "/24" represents the subnet mask, indicating that the first 24 bits are designated for the network portion of the address, leaving 32 - 24 = 8 bits for host addresses.

Since each octet in an IP address consists of 8 bits, in this case, the last octet is fully dedicated to host addresses. With 2^8 possible combinations (256 total values for an 8-bit number), there are 256 IP addresses in the CIDR block 10.0.0.0/24.
(Source: ChatGPT)

[What Is Network Segmentation and Why It Matters?](https://www.comptia.org/blog/security-awareness-training-network-segmentation)

1. In your own words, describe network segmentation.

When the network is separated by different things/devices such as firewalls, switches and routers.

2. Network segmentation isn’t important as long as the network is using a well configured firewall. Do you agree? Why or why not?

I disagree because firewalls alone can't ensure full protection of systems and can become obsolete. Network segmentation allows for further security and isolation in the event that anomolies or attacks arise within the network or system.

3. What is a screened subnet?

A screened subnet is also known as a DMZ subnet: "This includes the subnetworks that expose externally facing systems – where the handshakes take place on your network. For example, it may include public-facing websites or other resources accessible via the internet. You want to separate things that the public can access from your local area network (LAN), as well as internal data that needs to be protected."

5. Cameras, ID card scanners, locked doors and biometrics are just a few examples of what type of security?

Physical (traditional)

## Things I want to know more about

CIDR notation and tools to easily utilize that information.
