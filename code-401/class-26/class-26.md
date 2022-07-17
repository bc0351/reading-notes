Reading: Component Based UI
===========================

Below you will find some reading material, code samples, and some additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

Reading
-------

[react hello world](https://facebook.github.io/react/docs/hello-world.html)

1.  What are the building blocks of a React app?

    ```
    Elements
    ```


2.  What is the difference between an element and a React component?

    ```
    React components accept props as inputs and return React elements.
    ```

3.  What are some advantages of React’s component based architecture?

    ```
    It's cheap, fast, and modular.
    ```


[introducing JSX](https://facebook.github.io/react/docs/introducing-jsx.html)

1.  What is JSX and why do we use it?

    ```
    syntax extension to JavaScript. It produces React elements.
    ```


2.  Describe the process of embedding JavaScript expressions in JSX.

    ```
    Javascript expressions are wrapped with curly braces in a JSX statement.
    ```


3.  Is it safe to embed user input in JSX? Explain.

    ```
    Yes. React DOM escapes any values embedded in JSX before render. Everything is converted to a string before being rendered.
    ```


[rendering elements](https://facebook.github.io/react/docs/rendering-elements.html)

1.  Explain what a React Component is to a non-technical friend.

    ```
    A React Component is a static piece of what one sees in the browser. 
    ```

2.  Describe mutability and React Components, specifically, how is the UI updated?

    ```
    React Components are immutable. Only those components that need to change to update have their states change.
    ```


3.  If changes are made to the UI, what does React update?

    ```
    Only the node whose contents have changed.
    ```


Bookmark and Review
-------------------

*   [sass cheatsheet](https://devhints.io/sass)
*   [react cheatsheet](https://devhints.io/react)
*   [another react cheatsheet](https://reactcheatsheet.com/)
