# What is OAuth

What is OAuth? **OAuth is the way a website share its services and assets with users**
Give an example of what using OAuth would look like. **An example would be is if you are trying to sign into a website and it offers you the ability to sign in using another websites information to sign you in.**
How does OAuth work? What are the steps that it takes to authenticate the user? **There are 12 steps given in the reading from CSO.  Here they are as per the page.  The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
The first site gives this token and secret to the initiating user’s client software.
The client’s software presents the request token and secret to their authorization provider `(which may or may not be the second site)`.
If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
The user approves `(or their software silently approves)` a particular transaction type at the first website.
The user is given an approved access token `(notice it’s no longer a request token)`.
The user gives the approved access token to the first website.
The first website gives the access token to the second website as proof of authentication on behalf of the user.
The second website lets the first website access their site on behalf of the user.
The user sees a successfully completed transaction occurring.
OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed `(for various reasons)`.**
What is OpenID? **Open ID is what allows a human to authenticate themselves as being human and not a machine signing in.**


# Authorization and Authentication flows

What is the difference between authorization and authentication? **Authentication is when a site confirm who you are as the user and authorization is when grants you access to the information at the site when you have ben athenticated.**
What is Authorization Code Flow? **These are the steps as per the reading on Autho Docs.  The user clicks Login within the regular web application.
Auth0's SDK redirects the user to the Auth0 Authorization Server `(/authorize endpoint)`.
Your Auth0 Authorization Server redirects the user to the login and authorization prompt.
The user authenticates using one of the configured login options and may see a consent page listing the permissions Auth0 will give to the regular web application.
Your Auth0 Authorization Server redirects the user back to the application with an authorization code, which is good for one use.
Auth0's SDK sends this code to the Auth0 Authorization Server `(/oauth/token endpoint)` along with the application's Client ID and Client Secret.
Your Auth0 Authorization Server verifies the code, Client ID, and Client Secret.
Your Auth0 Authorization Server responds with an ID Token and Access Token `(and optionally, a Refresh Token)`.
Your application can use the Access Token to call an API to access information about the user.
The API responds with requested data.
What is Authorization Code Flow with Proof Key for Code Exchange `(PKCE)`?**
What is Implicit Flow with Form Post?**It is a way to for requesting access tokens when a site is not able to store user information.  It is not recommended to use this.**
What is Client Credentials Flow? **These are permissions that an adiministartor gives to an application.**
What is Device Authorization Flow? **This is what gives a piece of harddware the ability to use athentication to use multiple apps.**
What is Resource Owner Password Flow? **This is what gives an application the ability to store the password**