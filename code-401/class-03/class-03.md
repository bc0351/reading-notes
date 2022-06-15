# **Readings: Express REST API**
Below you will find some reading material, code samples, and some additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## **Readings**

[Review: ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

1. Classes are a template for creating ____.

    ```
    creating objects
    ```

2. Can a class declaration be hoisted?

    ```
    no
    ```

3. How would you describe a constructor and contextual “this” to a non-technical friend?

    ```
    JavaScript word to define properties of an objects
    ```


[Using Express Routing](https://expressjs.com/en/guide/routing.html)

1. Within Express, what does routing refer to?

    ```
    endpoints/handlers for interfacing with client requests
    ```

2. What is the difference between a route path and a route method?

    ```
    route methods are derived from HTTP methods. route paths are defined endpoints used in conjunction with router methods.
    ```

3. When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

    ```
    passing control to next callback
    ```

[Express Routing](https://scotch.io/tutorials/learn-to-use-the-new-router-in-expressjs-4)

1. What is an Express Router?

    ```
    It is a mini express application without all the bells and whistles of an express application, just the routing stuff.
    ```

2. By what do we mean initialize express.Router() in an express server?

    ```
    could have a Router for our basic routes, authenticated routes, and even API routes
    ```

3. What do we use route middleware for?

    ```
    Route middleware in Express is a way to do something before a request is processed
    ```
