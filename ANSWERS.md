<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
    - box3 because it is the last of the multiple class selectors.
2. Describe the difference between `display: block;` and `display: inline;`.
    - Inline falls in-line (with text coming directly before and after on the same line) with text and height and weight settings don't make a difference. Block elements display like paragraphs and take up a whole line.
3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
    - The cross axis (vertical for row, horizontal for column).
4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
    - Fixed: Does not change style or size no matter the screen resolution or device. Will have scrollbars or be scrollable at smaller resolutions.
    - Adaptive: Uses different HTML files for different screen sizes, so that each for each screen size, the sections are adapted.
    - Fluid: Uses percentages, sections shrink on mobile or tablet to fit viewport.
    - Responsive: Combines the flow of adaptive and fluid; media queries set maximum or minimum widths of the viewport so that the display of content will change fluidly as the viewport changes width.
5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
    - This sets the desktop width of the content and makes it possible to design around a given size, then flex the width smaller and design for smaller resolutions.
