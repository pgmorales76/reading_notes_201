# Class 3 Reading Notes

## Why This Topic Matters

### Lists are important because they're used all the time. Knowing which type of list element to use in a particular context gives your code a professional appearance

### In order to create complex layouts in CSS, you need to understand the box model and its effects on HTML elements

### Storing multiple bits of data in fewer codeblocks make your code more efficient

## *When should you use an `unordered list` in your HTML document?*

### The `<ul>` element is for grouping a collection of items that do not have a numerical ordering, and their order in the list is meaningless

## *How do you change the `bullet style` of unordered list items?*

### The `type` attribute sets the bullet style for the list

## *When should you use an `ordered list` vs an `unordered list` in your HTML document?*

###

## *Describe two ways you can change the numbers on `list items` provided by an `ordered list`?*

### One attribute you can use is the `type` attribute, which will set the numbering type

### Another attribute you can use is the `reversed` attribute, which specifies the list's items are in reverese order. The list items will be numbered from high to low

[Learn HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

[Ordered Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)

[Unordered Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)

## *Describe the CSS properties of `margin` and `padding` as characters in a story. What is their role in a story titled: “The Box Model”?*

### The **margin area**, bounded by the margin edge, extends the border area to include an empty area used to separate the element from its neighbors. Its dimensions are the *margin-box width* and the *margin-box height*

### The **padding area**, bounded by the padding edge, extends the content area to include the element's padding. Its dimensions are the *padding-box width* and the *padding-box height*

## *List and describe the four parts of an HTML elements box as referred to by the `box model`.*

### The CSS box model as a whole applies to block boxes and defines how the different parts of a box — margin, border, padding, and content — work together to create a box that you can see on a page. Inline boxes use just some of the behavior defined in the box model

### Making up a block box in CSS we have the

### **Content box**: The area where your content is displayed; size it using properties like inline-size and block-size or width and height

### **Padding box**: The padding sits around the content as white space; size it using padding and related properties

### **Border box**: The border box wraps the content and any padding; size it using border and related properties

### **Margin box**: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using margin and related properties

![The CSS Box Model from Mozilla](/images/box_model.png)

[Learn CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)

[The Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)

## *What `data types` can you store inside of an `Array`?*

### An array can store various data types — strings, numbers, objects, and even other arrays

## *Is the `people` array a valid JavaScript array? If so, how can I access the values stored? If not, why?*

### Yes

### Items in an array are numbered, starting from zero. This number is called the item's *index*. So the first item has index 0, the second has index 1, and so on. You can access individual items in the array using bracket notation and supplying the item's index, in the same way that you accessed the letters in a string

    const shopping = ['bread', 'milk', 'cheese', 'hummus', 'noodles'];`
    console.log(shopping[0]);
    // returns "bread"`

## *List **five** shorthand operators for assignment in javascript and describe what they do.*

### The assignment operator (`x = f()`) is used to assign a value to a variable. The assignment operation evaluates to the assigned value

### The addition operator (`x += f()`) adds the value of the right operand to a variable and assigns the result to the variable. The types of the two operands determine the behavior of the addition assignment operator. Addition or concatenation is possible

### The subtraction operator (`x -= f()`) subtracts the value of the right operand from a variable and assigns the result to the variable

### The multiplication operator (`x *= f()`) multiplies a variable by the value of the right operand and assigns the result to the variable

### The division operator (`x /= f()`) divides a variable by the value of the right operand and assigns the result to the variable

### The remainder operator (`x %= f()`) divides a variable by the value of the right operand and assigns the remainder to the variable

## *Read the code below and evaluate the last `expression` and explain what the result would be and why.*

### The expression evaluates to `10dog` because, even though `c` is assigned the value of `false`, it doesn't print in `console.log();`. Therefore, what `console.log();` prints is `10dog`

## *Describe a real world example of when a conditional statement should be used in a JavaScript program.*

### If a user is required to input a password, the password must be correct for the user to proceed to their account page. You wouldn't want access to be granted if the password was incorrect.

## *Give an example of when a `Loop` is useful in JavaScript.*

### You're counting the number of days to an important occasion

[Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)

[Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)

[Operators and Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

[Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)

[Loops](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)

## Things I Want to Know More About

### If you're uncertain about whether items in a list need to be ordered, should you use the `<ul>` element?

### What are some easy methods to manipulate the box model to make styling easier?

### How are arrays used in most websites?

### Why doesn't the value of `false` print in `console.log();`?
