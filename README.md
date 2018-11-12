# You're a JavaScript Eventing Master

## Learning Goals

- Use JavaScript events to invoke actions
- Create JavaScript functions as "first-class" data
- Use event listeners and `onload`

## Introduction

So far, you have been using JavaScript to change elements in the DOM as
displayed in the browser. Most interaction with web sites does not happen
through Chrome tools, however, so now we'll take the JavaScript we wrote in the
previous section and learn how to use it inside of functions. Instead of
implementing behavior directly in the browswer, we'll use event listeners to
trigger behavior, just like in a real web application.

### Use JavaScript Events to Invoke Actions

As we've seen from experimenting with interactions in Chrome tools,
JavaScript can trigger actions. Some programs work with direct user
input, such as mouse and keyboard actions. That kind of input actually
comes in piece by piece, in real time, and the program is expected to
respond to it as it happens. With JavaScript events, this is possible!

### Create JavaScript Functions as "First-Class" Data

In JavaScript, functions are _objects_. They inherit from the Object
prototype and they can be assigned `key: value` pairs. These pairs
are referred to as properties and can themselves be functions. These
functions can be assigned to variables, they can be passed around as
arguments; they can even be assigned as the return values of other
functions. Basically, first-class data is able to can what everyone
else can do, and you will learn to harness this ability.

### Use Event Listeners and `onload`

Many times you'll want to call functions when a user clicks a link,
enters a form, scrolls, moves their mouse over an object, or any
other number of actions. These actions are called events. You can
set specific functions to run when the user performs an event. Event
listeners "listen" for an event and then initiate the function. `onload`
will enable you to call functions when the page loads.

## Conclusion

JavaScript is a powerful resource that not only manipulates HTML and CSS, but it
can create be used in a number of applications with these functions and tools
universal tools built into it and browsers. By the time you complete this
section, you'll be a JavaScript eventing master.
