**1. When is Basic Authorization used vs. Bearer Authorization?**
- Basic Auth: most straightforward and easiest method for authentication, but rarely recommended due to security vulnerablities.  Does not require cookies, session ID's, login p ages, and other speciality solutions.
- Bearer Auth: the recommended Authentication method for whenever possible. It is ideal when scripting, when developing external app or when doing integration with external tools.

[Ref](https://blog.restcase.com/4-most-used-rest-api-authentication-methods/)

**2. What does the JSON Web Token package do?**
used to verify web tokens(can be used to verify a token asyncrhonously if ```callback``` is provided or synchronously if it is not)
[Ref 1](https://medium.com/swlh/using-the-jsonwebtoken-node-package-to-verify-json-web-tokens-497ecdaba830)
[Ref 2](https://auth0.com/docs/tokens/json-web-tokens)

**3. What considerations should we make when creating and storing a SECRET?**
- never store unecrypted secrets in .git repositories
- don't share your secrets unencrypted in messaging systems like Slack
- restrict AP access and permissions
[Ref](https://blog.gitguardian.com/secrets-api-management/)

# Vocabulary

**encyrption**
the process of converting a message from plaintext into ciphertext. The purpose of encryption is to make sure that a message cannot be understood by a third party.
[Ref](https://isaaccomputerscience.org/concepts/data_encrypt_encryption)

**token**
a peripheral device used to gain access to an electronically restricted resource.
[Ref](https://en.wikipedia.org/wiki/Security_token)

**bearer**
(also called token authentication) is an HTTP authentication scheme that involves security tokens called bearer tokens. 
[Ref](https://swagger.io/docs/specification/authentication/bearer-authentication/)

**secret**
A generic term for any secret value that an attacker could use to impersonate the subscriber in an authentication protocol.
[Ref](https://csrc.nist.gov/glossary/term/Authentication_Secret)

**JSON Web Token**
an Internet proposed standard for creating data with optional signature and/or optional encryption whose payload holds JSON that asserts some number of claims. 
[Ref](https://en.wikipedia.org/wiki/JSON_Web_Token)

# Preview
**1. Which 3 things had you heard about previously and now have better clarity on?**
- What RBAC is
- What RBAC uses are
- What RBAC's benefits are

**1. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
- how RBAC will be used with Auth0
- how to implement RBAC
- how to best utilize RBAC for security
- 
**1. What are you most excited about trying to implement or see how it works?**
- Using RBAC with Auth0.