Reading: Advanced State with Reducers
=====================================

Below you will find some reading material, code samples, and some additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

Reading
-------

[useReducer hook](https://reactjs.org/docs/hooks-reference.html#usereducer)

1.  Name an alternative to the `useState` Hook.

    ```
    useReducer
    ```

2.  Why might the `useReducer` Hook be preferable to the `useState` Hook?

    ```
    useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.
    ```

3.  What are two ways to set the initial state?

    ```
    1. Pass initial state as a second argument.

    2. Lay initialization -> init()
    ```


[Ultimate Guide to useReducer](https://blog.logrocket.com/guide-to-react-usereducer-hook/)

1.  In terms of state, what does `useReducer` expect to receive as a parameter?

    ```
    reducer function as its first parameter and the initial state as the second.
    ```

2.  What does `useReducer` return?

    ```
    array that holds the current state value and a dispatch function to which you can pass an action and later invoke it.
    ```

3.  Explain `dispatch` to a non-technical recruiter.

    ```
    The dispatch function accepts an object that represents the type of action we want to execute when it is called. Basically, it sends the type of action to the reducer function to perform its job, which, of course, is updating the state.
    ```
