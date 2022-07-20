Reading: Component Lifecycle / `useEffect` Hook
===============================================

Below you will find some reading material, code samples, and some additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

Reading
-------

[effects hook](https://reactjs.org/docs/hooks-effect.html)

1.  What purpose does `useEffect` serve in a function component compared to its counterpart(s) in class components?

    ```
    The Effect Hook lets you perform side effects in function components.
    ```


2.  When using the useEffect Hook:
    1.  What does `useEffect` do?

        ```
        By using this Hook, you tell React that your component needs to do something after render. React will remember the function you passed (we’ll refer to it as our “effect”), and call it later after performing the DOM updates.
        ```

    2.  Why is `useEffect` called inside a component?

        ```
        Placing useEffect inside the component lets us access the count state variable (or any props) right from the effect. We don’t need a special API to read it — it’s already in the function scope. Hooks embrace JavaScript closures and avoid introducing React-specific APIs where JavaScript already provides a solution.
        ```

3.  Explain the importance of properly implementing effects with Cleanup

    ```
    We might want to set up a subscription to some external data source. In that case, it is important to clean up so that we don’t introduce a memory leak! 
    ```
