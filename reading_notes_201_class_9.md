# Class 9 Reading Notes

## Why This Topic Matters

### Adding forms to webpages affords the user the opportunity to interact with the page, thus making the experience more enjoyable

### By bringing together HTML and JS in this context, a developer is able to manipulate the page, dynamically, based on what the user inputs

## *Why are forms so important in web development?*

### Web forms are one of the main points of interaction between a user and a website or application

## *When designing a form, what are some key things to keep in mind when it comes to user experience?*

### The bigger your form, the more you risk frustrating people and losing users. Keep it simple and stay focused: ask only for the data you absolutely need

## *List 5 form elements and explain their importance.*

### The `<form>` Element

#### This element formally defines a form. It's a container element like a `<section>` or `<footer>` element, but specifically for containing forms; it also supports some specific attributes to configure the way the form behaves

### The `<label>` Element

#### This element represents a caption for an item in a user interface

### The `<input>` Element

#### This element is used to create interactive controls for web-based forms in order to accept data from the user

### The `<textarea>` Element

#### This element represents a multi-line plain-text editing control, useful when you want to allow users to enter a sizeable amount of free-form text, for example a comment on a review or feedback form

### The `<button>` Element

#### This element is an interactive element activated by a user with a mouse, keyboard, finger, voice command, or other assistive technology. Once activated, it then performs a programmable action, such as submitting a form or opening a dialog

[HTML Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)

[Your first Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)

[How to Structure a Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)

## *How would you describe events to a non-technical friend?*

### Events are something that happens on a webpage by a user from a mouse, keyboard, finger, voice command, or other assistive technology

## *When using the `addEventListener()` method, what 2 arguments will you need to provide?*

### The name of the event we want to register this handler for, and the code that comprises the handler function we want to run in response to it

## *Describe the event object. Why is the target within the event object useful?*

### An event object is a parameter, inside an event handler function, specified with a name such as `event`, `evt`, or `e`. This is automatically passed to event handlers to provide extra features and information

## *What is the difference between event bubbling and event capturing?*

### In the **bubbling** phase, the exact opposite of the **capturing** phase occurs. The browser checks to see if the direct parent of the clicked element has a `click` event handler registered on it for the bubbling phase, and runs it if so. Then, it moves on to the next immediate ancestor element and does the same thing, then the next one, and so on until it reaches the `<html>` element

### In the **capturing** phase, the browser checks to see if the element's outer-most ancestor (`<html>`) has a `click` event handler registered on it for the capturing phase, and runs it if so. Then it moves on to the next element inside `<html>` and does the same thing, then the next one, and so on until it reaches the direct parent of the element that was actually clicked

[Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)

[Introduction to Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

[HTML5 Input Types](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types)

[Event Reference and listings](https://developer.mozilla.org/en-US/docs/Web/Events)

## Things I Want to Know More About

### Of all the combinations of input types and attributes for the `<input>` element, which are the most used?

### Are there certain forms that are easier to style than others?

### Is this the beginning of learning how to develop websites that are in use, today, rather than the simple ones we've been developing?
