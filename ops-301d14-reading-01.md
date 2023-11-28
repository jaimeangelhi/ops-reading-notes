# Reading 1

[Layers of OSI Model](https://www.geeksforgeeks.org/open-systems-interconnection-model-osi/) 

1. What does “OSI” stand for?

Open Systems Interconnection

2. List the 7 layers of the OSI model and what each one is responsible for.

Application - implemented by network applications, which produce the data; also serves as a window for the application services to access the network and for displaying the received info to the user.
Presentation - data from the application layer is extracted here and manipulated as per the required format to transfer over the network
Session - establishes connection, maintenance of sessions, and authentication, and ensures security
Transport - provides services to application layer and takes services from network layer for end to end delivery of the complete message
Network - transmission of data from one host to other located in different networks through routing and logical addressing.
Data Link - node to node delivery of message for error free data transfer over the physical layer (uses LLC and MAC)
Physical - actual physical connection between the devices (bits) includes hub, repeater, modem, and cables.

3. Distinguish which layers are the “hardware layers”, and which layers are the “software layers”. What does that even mean?

The hardware layers are the bottom three or lower three layers - Network, Data Link, and Physical
The software layers are the Session, Presentation, and Application.

4. How can the OSI model be used in troubleshooting?

The OSI model can be used in troubleshooting by identifying where certain packets or processes of information are getting hung up or stuck.  Knowing the process and the differing means of this interconnectedness allows the user or admin to rectify any anomolies in the process.

[What is Wireshark and How is it Used?](https://www.comptia.org/content/articles/what-is-wireshark-and-how-to-use-it)

1. What is Wireshark?

Wireshark is a network packet capture tool that breaks down network packets and shows them in a detailed level for further analysis.

2. What is a packet?

A packet is a discrete unti of data in a typical ethernet network.

3. What 3 high-level things does Wireshark accomplish? How could these be used for nefarious purposes? For benevolent purposes?

Wireshark performs packet capture, filtering, and visualization.  It can be used for troubleshooting performance issues on a network, to trace connections, view contents of suspect network transactions and identify bursts of network traffic.

## Things I want to know more about

How to best utilize Wireshark.
