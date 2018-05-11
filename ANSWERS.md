<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?

box3 would have the most specificity weight and box would have the least.



2. Describe the difference between `display: block;` and `display: inline;`.

Display: block will take up the full width of the line, and start a line break before and after the element. Display: inline will only take as much width as the element needs, without a line break.



3. While using flexbox, what axis are you using when you use the property: `align-items: center`?

You are aligning along the cross axis. If the flex direction is row/row-reverse then the cross axis is vertical, if the flex direction is column/column-reverse then the cross axis is horizontal.



4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

A fixed layout has no breakpoints(media queries) and no % based layouts. Will not adapt to the screen size and has no accessibility.
An adaptive layout has breakpoints and no % based layouts. Multiple layouts are made for different screen sizes, but does not adapt until a new breakpoint is hit.
A fluid layout has no breakpoints but is fully % based. Will adapt to the screen size, but only by being squished or stretched. 
A responsive layout has breakpoints and is fully % based. Both fluid and adaptive, will work on any screen size.



5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

Having a max width set will keep everything in the container under that width(unless you override it with more specific styling) to avoid horizontal scrolling, and it allows you to use %'s on the elements to make the website fully responsive.