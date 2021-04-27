# Write the following steps in the correct order:

1. Register your application to get a client_id and client_secret
1. Ask the client if they want to sign in via a third party
1. Make a request to the access token endpoint
1. Redirect to a third party authentication endpoint
1. Make a request to a third-party API endpoint
1. Receive authorization code
1. Receive access token

**What can you do with an authorization code?**
authorize users for purchasing, selling, or transferring of items

**What can you do with an access token?**
authorize specific applications to make AP requests on behalf of a user via access to specific parts of their data
[Ref](https://www.oauth.com/oauth2-servers/access-tokens/#:~:text=Access%20tokens%20are%20the%20thing,in%20transit%20and%20in%20storage.)

**What’s a benefit of using OAuth instead of your own basic authentication?**
**Features of OAuth 2.0**
1. It allows you to read data of a user from another application.
1. It supplies the authorization workflow for web, desktop applications, and mobile devices.
1. Is a server side web app that uses authorization code and does not interact with user credentials.
1. It gives users more control over their data; they can selectively grant access to various functionalities for applications they want to use.

**Advantages of OAuth 2.0**
1. This flexible protocol relies on SSL (Secure Sockets Layer) to ensure data between the web server and browsers remain private.
1. SSL uses cryptography industry protocols to keep data safe.
1. It uses tokenization to give limited access to the user's data. For example, instead of storing credit card information on Amazon’s web site, the credit card number, security code and consumer name are each given “token” IDs. The tokens are given to the merchant, not the actual data.
1. It is easy to implement and provides strong authentication. In addition to the two-factor authentication, tokens can be revoked if necessary (ie, suspicious activity).
1. Uses single sign on
[Ref](https://www.clowder.com/post/why-your-organization-should-be-using-oauth-2.0#:~:text=Integrating%20OAuth%202.0%20into%20your,not%20interact%20with%20user%20credentials.)

# Vocabulary
**Client ID**
a public identifier for apps.  Even though it’s public, it’s best that it isn’t guessable by third parties, so many implementations use something like a 32-character hex string. It must also be unique across all clients that the authorization server handles. If the client ID is guessable, it makes it slightly easier to craft phishing attacks against arbitrary applications.
[Ref](https://www.oauth.com/oauth2-servers/client-registration/client-id-secret/)

**Client Secret**
a secret known only to the application and the authorization server. It must be sufficiently random to not be guessable.
[Ref](https://www.oauth.com/oauth2-servers/client-registration/client-id-secret/)

**Authentication Endpoint**
an authentication mechanism used to verify the identity of a network's external or remote connecting device. This method ensures that only valid or authorized endpoint devices are connected to a network.
[Ref](https://www.techopedia.com/definition/23918/endpoint-authentication)

**Access Token Endpoint**
where apps make a request to get an access token for a user.

**API Endpoint**
the point of entry in a communication channel when two systems are interacting.  It refers to touchpoints of the communication between an API and a server. 
[Ref](https://rapidapi.com/blog/api-glossary/endpoint/#:~:text=In%20simple%20terms%2C%20an%20API,an%20API%20and%20a%20server.)

**Authorization Code**
an alphanumeric password that authorizes its user to purchase, sell or transfer items, or to enter information into a security-protected space. An authorization code is typically a sequence of letters, numbers, or a combination of both, that validates a person's identity, approves a transaction or provides access to a secured area.
[Ref](https://www.investopedia.com/terms/a/authorization-code.asp#:~:text=What%20Is%20an%20Authorization%20Code,into%20a%20security%2Dprotected%20space.)

**Access Token**
an object encapsulating the security identity of a process or thread.[1] A token is used to make security decisions and to store tamper-proof information about some system entity.
[Ref](https://en.wikipedia.org/wiki/Access_token#:~:text=An%20access%20token%20is%20an,information%20about%20some%20system%20entity.)

# Preview
**1. Which 3 things had you heard about previously and now have better clarity on?**
- JSON Web Tokens

**1. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
- JWT's and how secure they are
**1. What are you most excited about trying to implement or see how it works?**
- seeing how tokens are used in code in general
