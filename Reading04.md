# Class 04

## React Docs - Forms

In HTML, form elements such as <input>, <textarea>, and <select> typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState().

In React, a <textarea> uses a value attribute instead. This way, a form using a <textarea> can be written very similarly to a form that uses a single-line input

React, instead of using this selected attribute, uses a value attribute on the root select tag. This is more convenient in a controlled component because you only need to update it in one place.

## Conditional (Ternary) Operator Explained

You can shorten if statements into one line of code using Conditional Operators

ex:

if ( condition ) {
  value if true;
} else {
  value if false;
}

condition ? value if true : value if false

These both mean the same thing

The condition is what you’re actually testing. The result of your condition should be true or false or at least coerce to either boolean value.
A ? separates our conditional from our true value. Anything between the ? and the : is what is executed if the condition evaluates to true.
Finally a : colon. If your condition evaluates to false, any code after the colon is executed.