# Class 6 Reading Notes

## Why This Topic Matters

### This topic matters because we are learning how to access user input data in the most efficient way possible. This is central to the interactivity of JS

## *How would you describe an object to a non-technical friend you grew up with?*

### Objects are a collection of element pairs. Within the element pairs are property names, separated by a ":", and property values. Properties are identified using key values

## *What are some advantages to creating object literals?*

### It is very common to create an object using an object literal when you want to transfer a series of structured, related data items in some manner, for example sending a request to the server to be put into a database. Sending a single object is much more efficient than sending several items individually, and it is easier to work with than an array, when you want to identify individual items by name

## *How do objects differ from arrays?*

### Arrays are a type of object. Arrays are an ordered collection of data. Objects are a collection of properties

## *Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.*

### If an object property name is held in a variable, then you can't use dot notation to access the value, but you can access the value using bracket notation

### You use brackets for defining an array. You use curly braces for defining an object. You would use the dot notation for accessing properties of an object

## *Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?*

    // This is the dog object
    const dog = {
        name: 'Spot',
        age: 2,
        color: 'white with black spots',
        humanAge: function (){
        console.log(`${this.name} is ${this.age*7} in human years`);
        }
    }

### The this keyword refers to the current object the code is being written inside. When you only have to create a single object literal, it's not so useful. But if you create more than one, this enables you to use the same method definition for every object you create

[Javascript Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

## *What is the DOM?*

### The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page

## *Briefly describe the relationship between the DOM and JavaScript.*

### The DOM is not a programming language, but without it, the JavaScript language wouldn't have any model or notion of web pages, HTML documents, SVG documents, and their component parts. The document as a whole, the head, tables within the document, table headers, text within the table cells, and all other elements in a document are parts of the document object model for that document. They can all be accessed and manipulated using the DOM and a scripting language like JavaScript

[Introduction to the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

[Understanding the Problem Domain is the Hardest Part of Programming](https://simpleprogrammer.com/solving-problems-breaking-it-down/)

[What's the Difference Between Primitive Values and Object References in Javascript?](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)

## Things I Want to Know More About

### What do websites use more often, objects or arrays? Are there certain types of sites that prefer one over the other?

### What is an API? How often are these used in web development?
