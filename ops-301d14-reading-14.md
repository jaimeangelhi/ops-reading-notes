# Reading 14

1. What role does Group Policy play in Windows Active Directory?

"Group Policy is a feature of Windows that facilitates a wide variety of advanced settings that network administrators can use to control the working environment of users and computer accounts in Active Directory. It essentially provides a centralized place for administrators to manage and configure operating systems, applications, and users’ settings." (https://www.lepide.com/blog/what-is-group-policy-gpo-and-what-role-does-it-play-in-data-security/)

2. Name and describe different ways GPOs can benefit security.

-"A Group Policy Object could be used to determine the home page that a user sees when they launch their internet browser after logging onto the domain.
-Administrators can use GPOs to define which network-connected printers appear on the list of available printers after a user in a specific Active Directory OU logs onto the domain.
-Admins can also use GPOs to tweak a number of security protocols and practices, such as restricting internet connection options, programs, and even screen time."

3. How can the acronym “LSDOU” help you figure out which policies are in effect?

"local, site, domain, and organizational unit. The local computer policy is the first to be processed, followed by the site level to domain AD policies, then finally into organization units. If there happen to be conflicting policies in LSDOU, the last applied policies win out."

## Things I want to know more about

How does this translate to other systems than windows.
