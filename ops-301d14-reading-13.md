# Reading 13

1. What exactly is “Active Directory” and are the key services it provides?

It is the core Active Directory service used to manage users and resources in the identities and directories of Microsoft's Windows Domain Network.

2. What are the differences between a domain, forest, and tree in Active Directory?

Domain: "A domain is a collection of objects (e.g. users, devices) that share the same Active Directory database. A domain is identified by a DNS name like company.com."

Forest: "A forest is a collection of one or more trees that share a common schema, global catalog, and directory configuration—but aren’t part of a contiguous namespace. The forest typically serves as the security boundary for an enterprise network."

Tree: "A tree is a collection of one or more domains with a contiguous namespace (they have a common DNS root name like marketing.company.com, engineering.company.com, and sales.company.com)."

3. How can objects (e.g. users, devices) within a domain be grouped?

"Objects within a domain can be grouped into organizational units (OUs) to simplify administration and policy management. Administrators can create arbitrary organizational units to mirror functional, geographical, or business structures, and then apply group policies to OUs to simplify administration. OUs also make it easier to delegate control over resources to various administrators."

4. Explain the benefits of Active Directory, as you would to a family member.

Its great for single sign on and allowing easy updates, access control, and app sharing (printers).  Basically it's all being taken care of by someone else and you get to reap the benefits while you're a user on the Active Directory managed by administrators.

## Things I want to know more about
Mac versions of this?

