Reading: API Integration
========================

Below you will find some reading material, code samples, and some additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

Reading
-------

*   [Review API Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/api-server/)

1.  Explain the different between a query string parameter and a path parameter.

    ```
    query string parameters will come after the question mark in the URI and can be made up of multiple fields.

    path parameters are given as part of the URL separated by slashes.
    ```

2.  What would our API URL with a path id parameter be given the following information:
    1.  Domain: `http://our-site.com`
    2.  `v3`
    3.  model name: `stuff`
    4.  id: `things`

    ```
    http://our-site.com/api/v3/stuff/things
    ```

3.  We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.

*   [Review Auth Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/auth-server/)

1.  Describe how you would use middleware to implement basic and bearer auth.

    > Basic authentication on the `/signin` route only.
    >
    > `app.post('/signin', basicAuthentication, (req, re) => {...})`

2.  Describe the handshake necessary to implement OAuth.

    > OAuth (3rd Party) to be used on the `/oauth` route only
    >
    > i.e. `app.get('/oauth', 0Auth, (req, res) => { ... })`
    >
    > Handles the handshake process from a 3rd party OAuth system

3.  Describe how Role Based Access Control works to a non-technical friend.

    > Your access depends on the role provisioned to you. The role is configured with the access to different systems/networks.
