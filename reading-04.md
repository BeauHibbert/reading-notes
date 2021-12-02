## What is a ‘Controlled Component’?
In a controlled component, the data or input form element is handled by the React component itself making it the “single source of truth”, whereas it would otherwise be rendered by the DOM in normal HTML
“In HTML, form elements such as <input>, <textarea>, and <select> typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState().
We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”.”

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
“Since the value attribute is set on our form element, the displayed value will always be this.state.value, making the React state the source of truth. Since handleChange runs on every keystroke to update the React state, the displayed value will update as the user types.” In case there is an event handler it is important to update as soon as they enter them.

## How do we target what the user is entering if we have an event handler on an input field?
We can use handleChange to re-render state on every keystroke the user inputs.

## ## Why would we use a ternary operator?
It is useful in for shortening the amount of code that needs to be written for conditional statements.

## Rewrite the following statement using a ternary statement:
x===y ? console.log(true) : console.log(false);
