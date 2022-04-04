# Notes from Read: 14 Diversity & Inclusion in the Tech Industry
[Home](README.md)

What is OAuth?
Open protocol that can be used to give different webpages a standardized method of authorization.

Give an example of what using OAuth would look like.
When websites want my GitHub access.

How does OAuth work? What are the steps that it takes to authenticate the user?
- checks if its the right person, has them log in, ask if they want to use that account/info, is yes then access is givin.

What is OpenID?
A type of authentication for logging into machines, It originally fell to the wayside because facebook connect did the same thing but was easier to understand who was controlling your login identity. It is now an authentication layer for OAuth.

Authorization and Authentication flows

What is the difference between authorization and authentication?
authorization: 'who are you?', authentication: 'do you have access to do this?'

What is Authorization Code Flow?
That is when a web app or something else exchanges an authorization code for a token.

What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
PKCE is a security extension for public clients to avoid malicious programme creeping into the computer

What is Implicit Flow with Form Post?
an alternative to the Authorization code flow, intended for public clients, often used with form post response mode.

What is Client Credentials Flow?
Machine to machine authentication, they pass along thier client ID and Secret to authenticate users.

What is Device Authorization Flow?
rather than authenticate directy it usues a external device to authenticate who the user is, typically a smart phone.

What is Resource Owner Password Flow?
The application handles the user login and password. Typically using an interactive form.
