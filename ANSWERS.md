<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
    1. Class "box3" has the most specificity weight.
2. Describe the difference between `display: block;` and `display: inline;`.
    2. `Display: block;` extends to the end of the container, pushing the next element to the next line. `Display: inline:` makes the element's container just big enough to fit the content of the box model for the element, which allows the next element to be on the same line.
3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
    3. Cross-Axis
4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
    4. Fixed = no breakpoints, no % based layout
        Adaptive = breakpoints but no % based layout
        Fluid = all % based, but no breakpoints
        Responsive = Breakpoints + % based layouts. This is the most popular type of layout.
5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
    5. Readability. If we don't use max-width on the outermost container, when the website is used on a large screen it will be difficult to read the site.