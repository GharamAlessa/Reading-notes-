# React lifecycle 
![](https://hackernoon.com/hn-images/1*HSisLuifMO6KbLfPOKtLow.jpeg)


## Handling Events
> Handling events with React elements is very similar to handling events on DOM elements. There are some syntax differences:

 + React events are named using camelCase, rather than lowercase.
 + With JSX you pass a function as the event handler, rather than a string.

When using React, you generally don’t need to call addEventListener to add listeners
to a DOM element after it is created. Instead, just provide a listener when the element is initially rendered.
#### *Passing Arguments to Event Handlers*
Inside a loop, it is common to want to pass an extra parameter to an event handler.
## What Is React?
> React is a declarative, efficient, and flexible JavaScript library for building user interfaces.
It lets you compose complex UIs from small and isolated pieces of code called “components”.
## State and Lifecycle
> Consider the ticking clock example from one of the previous sections. In Rendering Elements,
we have only learned one way to update the UI. We call ReactDOM.render() to change the rendered output

### Question answers
+ *Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?*
 > render happens first
+ *What is the very first thing to happen in the lifecycle of React?*
 > initialization -constructor(prop)
+ *Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates*
 > constructor,componentWillMount, render, componentDidMount,react Updates.
+ *What does componentDidMount do?*
 > it can render updates or changes to the component before loading the page for the first time. is useful in cases of modals and tooltips.
Things I want to know more about
react life cycle
+ *what each stage in the life sycle do
video questions and answers
What types of things can you pass in the props?*
    > diplaying a subtitle and a title to the user, or initilizing things.
+ *What is the big difference between props and state?*
    props can be changed outside the component but you manipulate state inside the component.
When do we re-render our application?*
> when we need to update the component bases on user interaction.
+ *What are some examples of things that we could store in state?*
> a counter.
