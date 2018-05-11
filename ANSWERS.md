<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
    As sibling selectors they are all of equal weight

2. Describe the difference between `display: block;` and `display: inline;`.
    A block element will take up the entire width of the container, inline elements fall into place beside each other

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
    The cross axis

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
    A fixed layout will not respond to the size of the viewport in any way. 
    An adaptive design adapts itself to fit various screen resolutions.
    A fluid design uses relative units like percents to maintain the layout while resizing elements to fit the resolution of the viewport.
    A responsive design uses media queries to creat breakpoints that change the layout of the design when the viewport reaches a given resolution.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
    max-width will allow the container to shrink down with the viewport size, simply declaring width will maintain the container size and create a horizontal scroll bar when the container is shrunk.
