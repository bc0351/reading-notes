# Class 04 Reading

## React Docs - Forms

1. What is a ‘Controlled Component’?

    * form elements whose mutable states are only updated with setState *

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

    * Update the state with responses as entered. Controlled Components have a dual state: user input is taken, and it also controls subsequent actions. *

3. How do we target what the user is entering if we have an event handler on an input field?

    * onChange={this.handleChange} *

## The Conditional (Ternary) Operator Explained

1. Why would we use a ternary operator?

    * brevity *

2. Rewrite the following statement using a ternary statement:

    * (x===y) ? console.log(true) : console.log(false) *

## Bookmark and Review

[[React Bootstrap - Forms]].([https://react-bootstrap.github.io/forms/overview/])

[[React Docs - conditional rendering]].([https://reactjs.org/docs/conditional-rendering.html])

## Things I want to know more about

Passing functions as props and states
