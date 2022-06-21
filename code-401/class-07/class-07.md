# Reading: Bearer Authorization
Below you will find some reading material, code samples, and some additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## **Reading**
[Intro to JWT](https://jwt.io/introduction/)

1. What is a JSON Web Token (JWT)?

    *JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.*

2. When should we use JSON Web Tokens?

    ```
    Most commonly, authorization. Secure information exchange.
    ```

3. Claims are expected in which structural component of a JWT?

    ```
    Payload.
    ```


[Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

1. If I get a JWT and I can decode the payload, how can we call that secure?

    ```
    Private keys are only known to a single party.
    ```


2. If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

    ```
    Hash.
    ```

3. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

    ```
    If the recipient knows the secret, validity can be checked with the SHA256 Has function.
    ```
### **Videos**
[JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)

1. Why use JWT?

    ```
    It is open standard and enables secure transfer of information between two parties.
    ```

2. JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

    ```
    There are no dependencies for transmission. Information can be sent and received from a variety of devices.
    ```

3. What are the three components (the structure) of a JWT signature?

    ```
    Header. Payload. Signature.
    ```

### **Bookmark and Review**
* [npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)
