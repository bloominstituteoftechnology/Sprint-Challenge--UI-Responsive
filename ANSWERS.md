<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
    A: Being sibling-selectors, from what I understand, .box1, .box2 and .box3 have equal weight? Since .box3 is at the end, it has the most specificity weight.

2. Describe the difference between `display: block;` and `display: inline;`.
    A: 'display: block;' will extend across the entire width of a page, but 'display: inline;' will take up as much space as it is defined to have and exist in the same line as the items that it is also contained with.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
    A: 'align-items: center' will be controlling the cross-axis of the flex container.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
    A:  Fixed       - no breakpoints, no % based layouts
        Adaptive    - breakpoints, but no % based layouts
        Fluid       - no breakpoints, everything is % based
        Responsive  - breakpoints + % based layouts 

5. Why do we need to use the CSS property max-width on the outer-most container in a responsive website?
    A:  The CSS property max-width is applied to the outer-most container of a responsive website to ensure that the elements contained within that container do NOT extend beyond that defined width. It is telling the container "do not get bigger than x width."