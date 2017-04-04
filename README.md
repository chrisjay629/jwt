# JWT

To help prepare for API authentication tomorrow, research [JSON Web Tokens](https://jwt.io) (known as JWTs). This should take about 30 minutes. Answer the following questions and submit this README as your homework:

1. What are the 3 parts of a JWT?


1. Header
2. Payload
3. Signature






2. What information does each part contain?

1) Header

The header  consists of two parts, the type of the token called JWT, and the hashing algorithm,
example :HMAC SHA256 or RSA.


or in code :

{
  "alg": "HS256",
  "typ": "JWT"

2) Payload

Contains statements about the entity or the user ,which along with has metadata,
3 types a carried.

Reserved: Mandatory or recommended
Public: Used by people usin JWT
Private: Used by parties that agree to share info.

}
3. Why do people use JWTs for authentication? A great resource to read would be https://jwt.io/introduction/.
They create routes for users that are more secure when logging in called tokens 
