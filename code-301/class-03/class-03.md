# Class 03 Reading

## React Docs - lists and keys

1. What does .map() return?

Array with callback function performed on each element of original array.

2. If I want to loop through an array and display each value in JSX, how do I do that in React?

Map function with JSX return on element.

3. Each list item needs a unique __key__.

4. What is the purpose of a key?

Makes object retrievable.


## The Spread Operator

1. What is the spread operator?

Copies/combines/destructures arrays and objects.

2. List 4 things that the spread operator can do.

copy, combine, update, split

3. Give an example of using the spread operator to combine two arrays.

**let** newArr = [...oldArr1, ...oldArr2];

4. Give an example of using the spread operator to add a new item to an array.

**let** itemArray = ['item 1', 'item 2', 'item 3'];
**let** newItem = 'new item';
**let** newArray = [...itemArray, ...newItem];

5. Give an example of using the spread operator to combine two objects into one.

**let** newObject = {...oldObject1, ...oldObject2};

## How to Pass Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?

Creates swap function.

2. In your own words, what does the increment function do?

Acts as swap memory to not violate state and props rules.

3. How can you pass a method from a parent component into a child component?

Recursive method call of parent-component method from child component.

4. How does the child component invoke a method that was passed to it from a parent component?

this.props.increment

## Things I want to know more about

Time penalties from all this abstraction when dealing with big data; how ReactJS compares to AngularJS in this regard.
