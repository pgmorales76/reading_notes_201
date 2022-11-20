# Class 11 Reading Notes

## Why This Topic Matters

### These concepts add interactivity to the user experience. They also make the webpage/website more enjoyable

## *Explain how the ability to use video and audio on the web has evolved since the early 2000s.*

### Technologies like Flash and Silverlight were the firsts to produce video content on the world wide web. Both of these had security and accessibility issues, and are now obsolete, in favor of native HTML solutions `<video>` and `<audio>` elements and the availability of JavaScript APIs

## *Describe the use of the `src` and `controls` attributes in the `<video>` element.*

### In the same way as for the `<img>` element, the `src` (source) attribute contains a path to the video you want to embed

### Users must be able to control video and audio playback. You must either use the `controls` attribute to include the browser's own control interface, or build your interface using the appropriate JavaScript API

## *Why is it important to have **fallback content** inside the `<video>` element?*

### This will be displayed if the browser accessing the page doesn't support the `<video>` element, allowing us to provide a fallback for older browsers

## *Write a very short story where `<audio>` and `<video>` are characters.*

### `<audio>` was offended by how `<video>` looked. `<video>` was offended by how `<audio>` sounded. They decided to not comment-in any more. They both were bugged too easily!

[Video and Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

## *How does Grid layout differ from Flex?*

### Flex is one-directinal (meaning it's directional orientation can be up/down **OR** left/right), whereas Grid is two-directional (meaning it's directional orientation may be up/down **AND** left/right)

## *Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.*

### **Grid Container** is the element on which `display: grid` is applied. It’s the direct parent of all the grid items

### **Grid Item** is the children (i.e. *direct* descendants) of the grid container

### **Grid Line** are the dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column

[A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

## *Besides making a site visually appealing across different screen sizes, why should developers make images responsive?*

### The general problem whereby you want to serve different cropped images in that way, for various layouts, is commonly known as the **art direction problem**

### Also, there's no need to embed large images on the page if it is being viewed on a mobile screen. And conversely, a small image starts to look grainy when displayed larger than its original size. This is called the *resolution switching problem*

### Conversely, it is unnecessary to display a large image on a screen significantly smaller than the size it was meant for. Doing so can waste bandwidth

### To make things more complicated, some devices have high resolution screens that need larger images than you might expect to display nicely

## *Define the following `<img>` attributes `srcset` and `sizes`. Write an example of how they are used.*

### `srcset` defines the set of images that will allow the browser to choose between images, and what size each image is

### `sizes` defines a set of media conditions (screen widths) and indicates what image size would be best to choose, when certain media conditions are true

## *How is `srcset` more helpful for responsive images than CSS or JavaScript?*

### Rather than taking an image of random size and resizing it (which may have unwanted/unintended consequences, as mentioned above) by providing several image sizes, this gives the browser much more flexibility and the user a better experience

[Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

[Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)

[Other Embedding Technologies](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies)

## Things I Want to Know More About

### How do video/audio elements affect accessibility?

### Does Grid make working with css easier?

### How do responsive images affect accessibility?