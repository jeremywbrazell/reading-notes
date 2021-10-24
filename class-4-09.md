# Authorization/Authentication

1. **What header(s) are used in authentication and authorization?**
Th request header
- [Authorization header](https://www.loginradius.com/blog/async/everything-you-want-to-know-about-authorization-headers/)

1. **What is safe to put into a JWT?**
ID or Access Tokens

1. **How are JWTs validated?**
- use any existing middleware for your web framework
- choose a third party library from JWT.io
- manually implement the checks described in specification RFC 7519 > 7.2 Validating a JWT
[Ref](https://auth0.com/docs/security/tokens/json-web-tokens/validate-json-web-tokens)

## Vocab

- **RBAC** (Role-Based Access Control): an approach to restricting system access to authorized users. It is an approach to implement mandatory access control (MAC) or discretionary access control (DAC)
- **3 Primary Rules Defined for RBAC**
1. Role assignment: A subject can exercise a permission only if the subject has selected or been assigned a role.
1. Role authorization: A subject's active role must be authorized for the subject. With rule 1 above, this rule ensures that users can take on only roles for which they are authorized.
1. Permission authorization: A subject can exercise a permission only if the permission is authorized for the subject's active role. With rules 1 and 2, this rule ensures that users can exercise only permissions for which they are authorized.
[Ref](https://en.wikipedia.org/wiki/Role-based_access_control)
- **User Roles:** permissions granted to users for various job functions
- **JWT Token:** a proposed Internet standard for creating data with optional signature and/or optional encryption whose payload holds JSON that asserts some number of claims
[Ref](https://en.wikipedia.org/wiki/JSON_Web_Token)


## Articles
1. **Which 3 things had you heard about previously and now have better clarity on?**
- how various roles are designated for users at large companies
- what other different levels of security there are
- how hackers break through levels of security (high level)
- 
1. **Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
- the world of cyber ops
- which companies use JWT's
- whether or not JWT's are the most secure

1. **What are you most excited about trying to implement or see how it works?**
- implementing other new levels of security (i.e. security questions, email validation, etc)

## Resources
- [JWT Best Practices](https://curity.io/resources/learn/jwt-best-practices/)
- [Getters, Setters & Virtuals](https://sequelize.org/master/manual/getters-setters-virtuals.html)
- [Sequelize Associations](https://sequelize.org/master/manual/assocs.html)
- [JWT Security Best Practices](https://curity.io/resources/learn/jwt-best-practices/)

