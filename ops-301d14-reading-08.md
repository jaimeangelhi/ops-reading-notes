# Reading 8

Computer Network - AAA (Authentication, Authorization and Accounting)

1. Explain each of the three A’s as you would to a non-technical family member. Use an analogy or a story.

AAA is a standard-based framework used to control who is permitted to use network resources (through authentication), what they are authorized to do (through authorization), and capture the actions performed while accessing the network (through accounting). It's like a concert, some people have a ticket in, but not everyone has a backstage pass (depends on their authorization), and depending on the pass, every scan shows where that person has been.

2. What should the administrator do if the ACS server fails to authenticate a user during AAA implementation?

"If the ACS server fails to authenticate, the administrator should mention using the local database of the device as a backup, in the method list, to implement AAA."

3. What is the role of the NAS in the AAA implementation using an ACS server? Use a diagram.

"The client or Network Access Server (NAS) sends authentication requests to the ACS server and the server takes the decision to allow the user to access the network resource or not according to the credentials provided by the user."

RADIUS Concepts

1. What are the benefits of using RADIUS for authentication and authorization?

Allows for a central database for all employees authentication and authorization granting better security and a single point for policy enactment.

2. What is RADIUS and what does it stand for?

"RADIUS (Remote Authentication Dial-In User Service) is a client-server protocol and software that enables remote access servers to communicate with a central server to authenticate dial-in users and authorize their access to the requested system or service."

3. Research: What encryption algorithms does RADIUS use?

Transport Layer Security (TLS), EAP (Extensible Authentication Protocol), Message Digest Algorithm (MD5), CHAP (Challenge-Handshake Authentication Protocol)

## Things I want to know more about

all of it.
