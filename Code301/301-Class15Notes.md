# Class 15 Notes

## What is OAuth?

It is a protocol that describes how servers and services can allow access to resources without sharing the logon credentials . 

## Give an example of what using OAuth would look like.

A user is sending a picture over email and as they attach the photo in your cloud the OAuth is seemlessly authinticating the logon to your cloud so that you can select it to the email service.

## How does OAuth work? What are the steps that it takes to authenticate the user?

1. The user identity is verified
2. the second site creates a one-time token
3. the token is given to the initiating user's client software
4. Software presents the request token the authorization provider
5. user may need to authenticate
6. the user is given an access token
7. the user gives the access toke to the first website and then given to the second website as proof of authentication
8. second websited gives aaccess to their site and the user sees succesful transaction.

## What is OpenID?

OpenID is  a standard decentralized authentication protocol that allows user to login  to multiple applications. Its liek a digitial identitity badge

## What is the difference between authorization and authentication?

authentication is verification of identity where authorization actually gives you access.

## What is Authorization Code Flow?

Authorization Code Flow us ab exachnging an authorization code for a token

## What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

Its an authentication and authorization flow designed to enhance security. the PKCE aspect is esentially an extra step where before creating the token request, the client generates a random string and computes its value.

## What is Implicit Flow with Form Post?

Its a form of authorization code flow for sites or applications which cannot scurely store client info

## What is Client Credentials Flow?

it is a flow for Machine to machine applications

## What is Device Authorization Flow?

Authentication where the user is given a ling they can click to authorize their device.

## What is Resource Owner Password Flow?

A flow where the password and user name are sent to the backend to be stored (Not Recommended)
