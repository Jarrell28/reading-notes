# Reading Notes

# Class 08 - Access Control List (ACL)

## 1. When is Basic Authorization used vs. Bearer Authorization?

- Basic Authorization is used to sign in a user via username and password into an application

- Bearer Authorization is used when a user is already signed in, and determines what permissions that user has


## 2. What does the JSON Web Token package do?

Resource - https://jwt.io/introduction

JWT provides tokens to be used in bearer authorization. These tokens contain encrytped information about users. Using the JWT library, you can decrypt this token and access user data.

## 3. What considerations should we make when creating and storing a SECRET?

Resource - https://itnext.io/how-to-store-passwords-and-api-keys-in-project-code-1eaf5cb235c9

The main consideration would be how we would store the SECRET key. The most common way to store these keys would be to save them as environment variables and setting a .gitignore file to ignore the .env file. This way, the key is not being exposed to anyone except the client machine. Another way we could store the SECRET would be to use Firebase. Firebase is protected and only applications that are signed with a certificate can access Firebase databases.


## Document the following Vocabulary Terms

- **encryption** - In cryptography, encryption is the process of encoding information. This process converts the original representation of the information, known as plaintext, into an alternative form known as ciphertext. Ideally, only authorized parties can decipher a ciphertext back to plaintext and access the original information. [Resource](https://en.wikipedia.org/wiki/Encryption)

- **token** - Token, an object (in software or in hardware) which represents the right to perform some operation. [Resource](https://en.wikipedia.org/wiki/Token)

- **bearer** -  Bearer authentication (also called token authentication) is an HTTP authentication scheme that involves security tokens called bearer tokens. [Resource](https://swagger.io/docs/specification/authentication/bearer-authentication/)

- **secret** - A secret key is the piece of information or parameter that is used to encrypt and decrypt messages in a symmetric, or secret-key, encryption. [Resource](https://www.techopedia.com/definition/24865/secret-key)

- **JSON Web Token** - JWT is an open standard that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. [Resource](https://jwt.io/introduction)
 

## Preview

1. Which 3 things had you heard about previously and now have better clarity on? I haven't heard of the term RBAC, but I am familiar with the concept

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? RBAC, ACL, Implementing in applicatio

3. What are you most excited about trying to implement or see how it works? Interested in applying ACL/RBAC in an application and learning best practices

