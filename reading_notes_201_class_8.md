# Class 8 Reading Notes

## Why This Topic Matters

### What user will appreciate, because they have no way knowing how difficult web development can be, is great styling, an engaging look for a webpage

### As impressive as the logic of your code may be, you must be able to understand the end-user isn't going to appreciate (or have any way of understanding) that aspect of the webpage. What they're going to care about is if they can find what it is they're looking for on a page, and if they have a pleasant aesthetic experience

### Most webpages aren't designed for us. They're designed for people **unlike** us. Don't fight reality. Work with it and make it your own

### Lastly, accessbility in design is **very** important. Always remember: don't assume the user is like you. You don't have to assume the user **ISN'T** like you, but just keeo in mind not everyone is experiencing the page the way you do. Make as accessible as possible. Good design achieves that!

## *Flexbox is designed for one-dimensional content. Explain what this means.*

### In the article, we're considering a sidebar that sits, inline, with some content. Due to viewport space limitations, this demonstrates the advantages of flexbox

### One-dimensional (one direction) content means either a row (x-axis) **OR** a column (y-axis). Two-dimensional (two directions) would mean a row (horizontal) **AND** a column (vertical)

### Flexbox excels at taking a bunch of items which have different sizes, and returning the best layout. Flexbox not only helps lay the sidebar and content out inline, but where there's not enough space remaining, the sidebar will break onto a new line

## *Explain the difference between the main axis and cross axis.*

![Main and Cross Axes](/images/main_and_cross_axes.svg)

### The main axis is the one set by your `flex-direction` property. If that is `row` your main axis is along the row, if it is `column` your main axis is along the column

### The cross axis runs perpendicular (in the other direction) to the main axis, so if `flex-direction` is `row` the cross axis runs along the column (and vice-versa)

## *How can using certain properties of flexbox negatively impact accessibility?*

### Exercise caution when using any properties that reorder the visual display away from how things are ordered in the HTML document

### The `row-reverse` and `column-reverse` values are a good example of this. The reordering only happens for the visual order, not the logical order. This is important to understand as the logical order is the order that a screen reader will read out the content, and anyone navigating using the keyboard will follow

## *What are some advantages of using flexbox over float?*

### Floats were used, originally, for floating images inside blocks of text. With better tools, it is used, today, for its original purpose

### Items flex (expand) to fill additional space or shrink to fit into smaller spaces

### Simple layout designs are either difficult, or impossible, to achieve with floats in any kind of convenient, flexible, way

## *How does this topic connect with your long term goals?*

### This gives me an idea as to which layout techniques are worth learning, first; then, which are worth learning at another time

[Learn CSS - Flexbox](https://web.dev/learn/css/flexbox/)

[CSS Layout - Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)

[Learn CSS - Layout](https://web.dev/learn/css/layout/)

## Things I Want to Know More About

### Is the best CSS layout always contextual, or is there, generally, one should strive to use?

### Even though their considered to be "legacy techniques", is it a good idea to learn the old layout formats, and be able to use them, if need be?
