# Class 2 Notes

## Why This Topic Matters

### Using the right HTML element, in the right place, makes for better code

### CSS needs to be structured a certain way for it to apply, properly

### JS data types assign certain values to variables to perform different functions

### Conditionals create different scenarios for a program to run

## *Why is it important to use semantic elements in our HTML?*

### It's a good idea to use the relevant HTML element for the job. We need to make sure we are using the correct elements, giving our content the correct meaning, function, or appearance. In this context, the `<h1>` element is also a semantic element, which gives the text it wraps around the role (or meaning) of "a top level heading on your page."

### By default, the browser will give it a large font size to make it look like a heading (although you could style it to look like anything you wanted using CSS). More importantly, its semantic value will be used in multiple ways, for example by search engines and screen readers

## *How many levels of headings are there in HTML?*

### 6

## *What are some uses for the `<sup>` and `<sub>` elements?*

### You will occasionally need to use superscript and subscript when marking up items like dates, chemical formulae, and mathematical equations so they have the correct meaning

## *When using the `<abbr>` element, what attribute must be added to provide the full expansion of the term?*

### If providing the expansion in addition to the abbreviation makes little sense, and the abbreviation or acronym is a fairly shortened term, provide the full expansion of the term as the value of `title` attribute

[Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)

[HTML Text Fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)

[HTML Advanced Text Formatting](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)

## *What are ways we can apply CSS to our HTML?*

### There are three methods of applying CSS to a document: with an external stylesheet, with an internal stylesheet, and with inline styles

## *Why should we avoid using inline styles?*

### First, it is the least efficient implementation of CSS for maintenance. One styling change might require multiple edits within a single web page. Second, inline CSS also mixes (CSS) presentational code with HTML and content, making everything more difficult to read and understand. Separating code and content makes maintenance easier for all who work on the website

![Anatomy of a CSS ruleset by Mozilla](/images/anatomy_of_a_css_ruleset.png)

## *What is representing the selector?*

### `h2`

## *Which components are the CSS declarations?*

### The propery and the property value

## *Which components are considered properties?*

### `color` and `padding`

[How CSS is structured](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured)

## *What data type is a sequence of text enclosed in single quote marks?*

### A string

## *List 4 types of JavaScript operators.*

### Assignment (`=`), strict equality (`===`), not (`!`), and does not equal (`!==`)

## *Describe a real world problem you could solve with a function.*

### Prompting a user to enter a password; alerting the user their input is invalid, adding an image changer, or adding a personalized welcome message

[Javascript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics#comments)

## *An if statement checks a __ and if it evaluates to ___, then the code block will execute.*

### conditioon; `true`

## *What is the use of an `else if`?*

### If the `if` statement condition evaluates to `false`, the `else if` statement provides another condition for the program to evaluate

### There is a way to chain on extra choices/outcomes to your `if...else` — using `else if`. Each extra choice requires an additional block to put in between `if () { }` and `else { }`

[What are the differences between if, else, and else if? Stack Overflow](https://stackoverflow.com/questions/1439907/what-are-the-differences-between-if-else-and-else-if)

## *List 3 different types of comparison operators.*

### `===` and `!==` — test if one value is identical to, or not identical to, another

### `<` and `>` — test if one value is less than or greater than another

### `<=` and `>=` — test if one value is less than or equal to, or greater than or equal to, another

## *What is the difference between the logical operator `&&` and `||`?*

### `&&` — AND; allows you to chain together two or more expressions so that all of them have to individually evaluate to `true` for the whole expression to return `true`

### `||` — OR; allows you to chain together two or more expressions so that one or more of them have to individually evaluate to `true` for the whole expression to return `true`

[Making Your Decisions In Your Code - Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)

## Things I Want to Know More About

### When, if ever, should non-semantic elements be utilized?

### When, if ever, should inline styling be utilized?

### Functions in the DOM

[How to Write a Git Commit Message](https://cbea.ms/git-commit/)
