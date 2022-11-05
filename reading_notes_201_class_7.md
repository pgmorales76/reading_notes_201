# Class 7 Reading Notes

## Why This Topic Matters

### Answering the call of the question is the first step in solving the issue at hand. If you don't know the problem, you can't possibly solve it

### Creating tables in HTML documents is an important skill to present data, effectively

### Constructors allow the developer to create many objects without having to write out too much code

## *Explain why we need domain modeling.*

### A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams

## *Why should tables not be used for page layouts?*

### Layout tables reduce accessibility for visually impaired users, tables produce tag soup, and tables are not automatically responsive

## *List and describe 3 different semantic HTML elements used in an HTML `<table>`.*

### The table header (`<th>`) HTML element defines a cell as header of a group of table cells. The exact nature of this group is defined by the scope and headers attributes

### The table data cell (`<td>`) HTML element defines a cell of a table that contains data. It participates in the table model

### The table row (`<tr>`) HTML element defines a row of cells in a table. The row's cells can then be established using a mix of `<td>` (data cell) and `<th>` (header cell) elements

## *What is a constructor and what are some advantages to using it?*

### A constructor belongs to a particular object that's been created. The constructor initializes the object and provides access to its data

### The reason to use constructors is if you're creating more than one object, you don't have to write out the same code for every object created; and, if you want to change some properties of the object - like adding a height property - then you have to remember to update every object

## *How does the term `this` differ when used in an object literal versus when used in a constructor?*

### `this` enables you to use the same method definition for every object you create

### When a constructor function is called, using the `new` keyword, the constructor will bind `this` to the new object, so you can refer to `this` in the constructor code

## *Explain prototypes and inheritance via an analogy from your previous work experience.*

### Prototypes are properties that link to another object. This is the beginning of the **prototype chain**

### Inheritance acts in JS as a way of matching a property name to a prototype object. This seems to be similat to inheritance in CSS

[Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

[HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

[Introducing Constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)

[Object Prototypes](https://ui.dev/beginners-guide-to-javascript-prototype)

[HTML Table Advanced Features and Accessibility](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)

## Things I Want to Know More About

### Does the domain model constantly change, as a project changes?

### Does the `new` keyword replace `this` when using constructors?

### It seems prototypes can go on and on. Is this ever seen?
