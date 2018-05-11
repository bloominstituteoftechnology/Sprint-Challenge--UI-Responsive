<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
box3

2. Describe the difference between `display: block;` and `display: inline;`.
display:block takes up the whole line while inline only takes up space it needs.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
cross axis

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
A fixed layout is static and nothing changes when the page changes in size.
An adaptive layout changes depending on the size of the window and has several fixed layouts.
A fluid layout is percent based and also changes depending on the size of the window, downside is that it squishes and
can be hard to read.
A responsive layout is like the fluid and adaptive layouts combined. It uses media queries to change the layout
depending on the size of the screen.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
Because css reads from top to bottom and it would be overwritten otherwise.
