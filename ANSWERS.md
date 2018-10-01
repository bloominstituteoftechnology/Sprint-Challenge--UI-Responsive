<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
    "box"
2. Describe the difference between `display: block;` and `display: inline;`.
    When we use `display: block` each html element will appear in a new line, while using `display: inline` will render each element next to each other until they fill the whole width of the line.
3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
    The cross axis.
4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
    fixed layout:
        The website has a wrapper which is always have the same sizes(fixed size), which means the website is optimized to certain screen size(s).
    adaptive layout:
        Adaptive design is when a website changes it's look based on breakpoints. For example the website looks the same at a width of 600px and 639px, but will adapt to a new design at 640px width.
    fluid layout:
        As we resize the window the layout of the website is also changing according to the window size.
    responsive layout:
        The combination of the above used techniques.
5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
    So it won't overfill.