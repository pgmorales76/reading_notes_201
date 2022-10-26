# Class 4 Reading Notes

## Why This Topic Matters

### Links are make the web, a web! The very first web technology, HTML, is based off the idea of linking information between users. Without links, there no web to be world-wide

## *To create a basic link, we wrap text or other content inside what element?*

### A basic link is created by wrapping the text or other content, inside an `<a>` element and using the `href` attribute, also known as a **Hypertext Reference**, or **target**, that contains the web address

    <p>
        I'm creating a link to
        <a href="https://www.mozilla.org/en-US/">the Mozilla homepage</a>.
    </p>

## *The `href` attribute contains what information?*

### The URL that the hyperlink points to

## *What are some ways we can ensure links on our pages are accessible to all readers?*

### The content inside a link should indicate where the link goes, even out of context

### You should only use a hyperlink for navigation to a real URL

### Links that open in a new tab/window via `target="_blank"`, or links that point to a download file should indicate what will happen when the link is followed

### Skip links could be used to let keyboard users bypass content repeated throughout multiple pages, such as header navigation

### Interactive elements, like links, should provide an area large enough that it is easy to activate them

### Interactive elements, like links, placed in close visual proximity should have space separating them

[Learn HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML)

[Creating Hyperlinks](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)

## *What is meant by “normal flow”?*

### Elements on a webpage lay out in normal flow if you haven't applied any CSS to change the way they behave

## *What are a few differences between `block-level` and `inline` elements?*

### By default, a block level element's content fills the available inline space of the parent element containing it and grows along the block dimension to accommodate its content. The size of Inline elements is just the size of their content

## *___ positioning is the default for every html element*

### Static positioning is the default that every element gets. It just means "put the element into its normal position in the document flow — nothing special to see here."

## *Name a few advantages to using absolute positioning on an element*

### An absolutely positioned element no longer exists in the normal document flow. Instead, it sits on its own layer separate from everything else. This is very useful: it means that we can create isolated UI features that don't interfere with the layout of other elements on the page

### `top`, `bottom`, `left`, and `right` behave in a different way with absolute positioning. Rather than positioning the element based on its relative position within the normal document flow, they specify the distance the element should be from each of the containing element's sides

## *What is a key difference between fixed positioning and absolute positioning?*

### where **absolute positioning** fixes an element in place relative to its nearest positioned ancestor (the initial containing block if there isn't one), **fixed positioning** usually fixes an element in place relative to the visible portion of the viewport. This means that you can create useful UI items that are fixed in place, like persistent navigation menus that are always visible no matter how much the page scrolls

[CSS Layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout)

[CSS Layout: Normal Flow](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow)

[CSS Layout: Positioning](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning)

## *Describe the difference between a function declaration and a function invocation.*

### A function declaration is, simply, creating a function in code

### To actually use a function after it has been defined, you've got to run — or invoke — it. This is done by including the name of the function in the code somewhere, followed by parentheses

## *What is the difference between a parameter and an argument?*

### A parameter is a value that needg to be included inside the function parentheses, which it needs to do its job properly

### An argument is an input expression supplied to a function

[Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)

[Functions – Reusable Blocks of Code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions)

## *Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.*

### Engaged collaboration is useful to help me stay on track and not waste time trying to figure the problem out when help could be sought

### Learning from fellow students brings a new perspective (and different knowledge) to the process. We all come to this from different paths. Learning from the path of others makes out journey more enjoyable

[6 Reasons for Paired Programming](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)

## Things I Want to Know More About

### How do links stay up-to-date?

### Is there a best flow state for CSS?

### Does the syntax of functions change that much across programming languages, or is it the same?
