Readings: Authentication
========================

Below you will find some reading material, code samples, and some additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

Readings
--------

[Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

1.  Explain to a non-technical friend how you would safely hash and store a password.
    
    ```
    1. Use a hashing algorithm to pseudo-randomize a password
    2. 'Salt' the hashed password to pseudo-randomize further
    3. Store the salted, hashed password in a database
    ```


2.  What is Bcrypt?

    ```
     Bcrypt is an adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces a work factor (also known as security factor), which allows you to determine how expensive the hash function will be.
    ```

3.  Why might you use something like Bcrypt?

    ```
    If the threat risk of brute force attacks is elevated for a particular application.
    ```

[Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)

1.  What is Basic Authentication?

    <p>In the context of an <a href="/wiki/HTTP" class="mw-redirect" title="HTTP">HTTP</a> transaction, <b>basic access authentication</b> is a method for an <a href="/wiki/User_agent" title="User agent">HTTP user agent</a> (e.g. a <a href="/wiki/Web_browser" title="Web browser">web browser</a>) to provide a <a href="/wiki/User_name" class="mw-redirect" title="User name">user name</a> and <a href="/wiki/Password" title="Password">password</a> when making a request. In basic HTTP authentication, a request contains a header field in the form of <code>Authorization: Basic &lt;credentials&gt;</code>, where credentials is the <a href="/wiki/Base64" title="Base64">Base64</a> encoding of ID and password joined by a single colon <code>:</code>.
    </p>

2.  What properties are necessary in the header of a Basic Auth request?

    ```
    1. The username and password are combined with a single colon (:). This means that the username itself cannot contain a colon.
    2. The resulting string is encoded into an octet sequence. The character set to use for this encoding is by default unspecified, as long as it is compatible with US-ASCII, but the server may suggest use of UTF-8 by sending the charset parameter.[9]
    3. The resulting string is encoded using a variant of Base64 (+/ and with padding).
    4. The authorization method and a space (e.g. "Basic ") is then prepended to the encoded string.
    ```

3.  How are`username:password`in Basic Auth encoded?

    ```
    Base64
    ```

[OWASP auth cheatsheet](https://www.owasp.org/index.php/Authentication_Cheat_Sheet)

1.  Define the authentication process to a non-technical recruiter.

    ```
    Authentication is the process of verifying that an individual, entity or website is whom it claims to be. Authentication in the context of web applications is commonly performed by submitting a username or ID and one or more items of private information that only a given user should know.

    It is a zero trust model.
    ```

2.  How should your error messaging respond (both HTTP and HTML)? Why?

    ```
    Incorrectly implemented error messages in the case of authentication functionality can be used for the purposes of user ID and password enumeration. An application should respond (both HTTP and HTML) in a generic manner.

    The objective is to prevent the creation of a discrepancy factor, allowing an attacker to mount a user enumeration action against the application.
    ```


3.  Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.

Bookmark and Review
-------------------

[bcrypt docs](https://www.npmjs.com/package/bcrypt)
