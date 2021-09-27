# Event Driven Applications

1. **Why is access control important?**
because it is a valuable security technique that can be used to regulate who or what can view or use any given resource. In an I.T security setting this could translate to who can access and edit a particular file, what kinds of equipment can be used or who can access certain devices. 
[Ref](https://premieritsolution.co.uk/the-important-of-access-control/#:~:text=Access%20control%20is%20important%20because,or%20use%20any%20given%20resource.&text=Without%20proper%20access%20control%20you,privacy%20and%20data%20protection%20laws.)

1. **Describe an application that would need access control.**
Entry into a building, laptops containing sensitive information, bank vaults, etc

1. **What is a role used for?**
to limit system access to authorized users based on specific needs and uses.

**RBAC Model**
S = Subject = A person or automated agent
R = Role = Job function or title which defines an authority level
P = Permissions = An approval of a mode of access to a resource
SE = Session = A mapping involving S, R and/or P
SA = Subject Assignment
PA = Permission Assignment
RH = Partially ordered Role Hierarchy. RH can also be written: ≥ (The notation: x ≥ y means that x inherits the permissions of y.)
A subject can have multiple roles.
A role can have multiple subjects.
A role can have many permissions.
A permission can be assigned to many roles.
An operation can be assigned to many permissions.
A permission can be assigned to many operations.

[Ref](https://en.wikipedia.org/wiki/Role-based_access_control)

1. **Why is role based access control more scalable than discretionary or mandatory access control?**
because access is assigned to particular job titles(having particular roles), not individuals

**DAC** = gives permissions control to the owner over any objects they own
**MAC** = most restrictive access whereby all end users permissions are controlled by system owners and adminstrators

# Vocab Terms

1. **Authorization**
the function of specifying access rights/privileges to resources, which is related to general information security and computer security, and to access control in particular
[Ref](https://en.wikipedia.org/wiki/Authorization)

1. **Role Based Access Control**
an approach to restricting system access to authorized users whereby access is determined by job role
[Ref](Vhttps://en.wikipedia.org/wiki/Role-based_access_control)

1. **Capabilities**
otherwise known as a key, is a communicable, unforgeable token of authority. It refers to a value that references an object along with an associated set of access rights.
[Ref](https://en.wikipedia.org/wiki/Capability-based_security)

# Preview
1. **Which 3 things had you heard about previously and now have better clarity on?**
- I had heard of OOP before and now I know a little bit about it and know that there is another approach known as EDP.

1. **Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
- Would like to get pointers on how to navigate this Node.js documentation or what I should be most familiar with because there is a lot in this documentation.

1. **What are you most excited about trying to implement or see how it works?**
- How to reference the [node.js](https://nodejs.org/api/events.html) doc.

**Other Docs**
[EDP & OOP](https://www.digitalocean.com/community/tutorials/nodejs-event-driven-programming)