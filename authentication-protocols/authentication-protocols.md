---
description: Authentication Protocols
---

# Authentication Protocols

Authentication Protocols

PAP \(Password Authentication Protocol\) -

Authentication is confirming something that is authentic or true.

In computers, authentication is the process of verifying the identity of a user such as a user name or password.

PAP is a simple authentication protocol.

It is compatible with about everything.

The downside is that it is not very safe.

All the sensitive data like usernames or passwords are sent in clear text.

CHAP \(Challenge Handshake Authentication Protocol\) -

It is a better alternative to PAP because it encrypts username and passwords.

This protocol authenticates by the server asking or challenging the client to validate itself by using a 3 way handshake.

After a connection has been made, the server sends a challenge to the client.

Then the client responds by using a one way hash function with the answer.

Then the server checks the response against its own calculation and if the value matches then the authentication is passed.

MS-CHAP \(Microsoft Challenge Handshake Protocol\) -

MS-CHAP is Microsoft’s version of CHAP.

There are two versions of MS-CHAP - MS-CHAP and MS-CHAP2

MS-CHAP - Basically CHAP \(Authenticates the client\).

MS-CHAP2 - Both the client and the server are authenticated so it’s more secure.

RADIUS \(Remote Authentication Dial-In Service\) -

It is a protocol that enables a single server, such as a domain controller to handle all authentication.

It allows a company to store user access data in a control location.

Users log into the radius server and that makes the request on the user’s behalf after authenticating.

Kerberos Authentication -

It is an authentication protocol that was developed by MIT.

It authenticates by using tickets.

In order for a client to access network resources, it first authenticates itself with the Kerberos server.

Then after authentication, client is issued a ticket which then gives the client access to the network resources.

EAP \(Extensible Authentication Protocol\) -

This is an extension to PPP.

It is a general protocol that supports many methods of authentication.

Commonly associated with Smart cards.

