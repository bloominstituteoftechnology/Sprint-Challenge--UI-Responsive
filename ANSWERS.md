<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?

    .box3

2. Describe the difference between `display: block;` and `display: inline;`.
 
    `display:block;` takes up the whole width of the container element while `display:inline` 
    allows for elements to co-exist on the same line without forcing other elements to get bumped down

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?

    cross-axis

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

    a fixed layout is rigid and hard-coded, which is horrible when many screen sizes are accsessing the site.
    an adaptive layout introduces media queries and adjusts for different screen sizes, but doesn't take into
    account a graceful transition between the hard coded media queries. a fluid layout introduces proportional
    units (percent values), but doesn't use media queries to truly customize the experience for each breakpoint.
    responsive layouts combine the best of adaptive and fluid layouts by customzing for each break point and handling
    any transitions between those breakpoints with percent values.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

   or else screen sizes with very large screens would stretch the container way too wide and the site would
   end up being a horrible experience.
