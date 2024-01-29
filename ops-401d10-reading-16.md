# Reading 16

1. What were the three commands used for the attack?

The three command codes used for the attack were "Get credentials", "List buckets", and "download files".

2. What misconfiguration of AWS components allowed the attacker to access sensitive data?

The misconfigurations of AWS components that allowed the attacker to access sensitive data involved a misconfigured WAF that enabled accessing the corresponding AWS EC2 instance/ECS task metadata using a server-side request forgery (SSRF) and called the metadata service endpoint using a specific url. The endpoint then returned a role (https://www.zscaler.com/resources/white-papers/capital-one-data-breach.pdf)

3. What are two of the AWS Governance practices that could have prevented such attack?

Two of the AWS governance practices that could have prevented such an attach were using cloud infrastructure entitlement managemetn (CIEM) solutions to automate detection of over-privileged identities and over-exposed data, automated policies for zscaler workload posture with cloud security posture management (CSPM).  Additional governance practices exist that would also help prevent or staunch such attacks.

## Things I want to know more about

Need to read through this article again to understand the fullness and complexities.
