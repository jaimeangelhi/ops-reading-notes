# Reading 10

1. How can one host within a VPC any services that need to be public?

"Some VPC providers offer additional customization with:

Network Address Translation (NAT): This feature matches private IP addresses to a public IP address for connections with the public Internet. With NAT, a public-facing website or application could run in a VPC." (https://www.cloudflare.com/learning/cloud/what-is-a-virtual-private-cloud/)


2. What are examples of services that would live in the publicly-accessible part of the VPC? The privately-accessible part?

Storage buckets, relational databases, and load balancers could all be hosted/live in the publicly accessible part of the vpc, and the privately hosted part would have more of the infrastructure, internal web applications, internal relational databases, etc.

3. What are the trade-offs of using a VPC vs traditional infrastructure?

The tradeoffs of using a VPC vs traditional infrastructure include scalability, cost efficiency, global reach, managed services, flexibility, for the challenges of internet dependence, security risks, data transfer costs, regulatory issues, and learning curves.


## Things I want to know more about
