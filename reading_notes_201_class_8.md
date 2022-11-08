# Class 8 Reading Notes

## Why This Topic Matters

###

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

###

## *How does this topic connect with your long term goals?*

### 

[Learn CSS - Flexbox](https://web.dev/learn/css/flexbox/)

[CSS Layout - Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)

[Learn CSS - Layout](https://web.dev/learn/css/layout/)

## Things I Want to Know More About

###

###
