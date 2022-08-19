# Class 05

## Thinking in React

Single-Responsibility Princeple : The single-responsibility principle (SRP) is a computer programming principle that states that "A module should be responsible to one, and only one, actor."[1] The term actor refers to a group (consisting of one or more stakeholders or users) that requires a change in the module.

React’s one-way data flow (also called one-way binding) keeps everything modular and fast.

State is reserved only for interactivity, that is, data that changes over time.

The components will only have render() methods since this is a static version of your app.

## Higher Order Functions

Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions. Since we have already seen that functions are regular values, there is nothing particularly remarkable about the fact that such functions exist. The term comes from mathematics, where the distinction between functions and other values is taken more seriously.

Higher-order functions allow us to abstract over actions, not just values.

One area where higher-order functions shine is data processing.

Another common thing to do with arrays is to compute a single value from them. Our recurring example, summing a collection of numbers, is an instance of this. Another example is finding the script with the most characters.

Being able to pass function values to other functions is a deeply useful aspect of JavaScript.