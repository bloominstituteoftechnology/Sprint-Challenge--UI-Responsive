<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
<!--.box3, as it is the furthest to the right-->

2. Describe the difference between `display: block;` and `display: inline;`.
<!-- display:block will cause an element to occupy the entire available space of its parent width-wise, preventing sibling elements from appearing horizontally to it, whereas a display:inline element will only occupy the space associated with its own width, allowing other elements to appear horizontally to it.-->

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
<!--Cross-axis-->

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
<!--
Fixed layout: No responsiveness, fixed widths for all elements

Adaptive layout: Uses media queries to reformat page at set break-points. This can mean shrinking, hiding, re-arranging, or reformatting elements, amongst other things. Once a break-point has been passed, the site will be in effect fixed until another break-point is reached.

Fluid-layout: Elements widths are set to percentages, and so re-set continuously with different sized viewports. However, this is their only change, and their are no breakpoints. This layout starts to run into issues at very thin viewports for most types of content.

Responsive: Responsive takes elements of both adaptive and fluid layouts. Essentially, the layout will be fluid within a breakpoint, but once a break-point is reached, the site can reformat similarly to an adaptive layout. Then in the new format, it will behave fluidly until a new break-point is reached.

-->

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
<!--
Otherwise the container would continue growing as the viewport did, and there is no reasonable limit on viewports baked into most browsers, so the design of all sites would fall apart at sufficiently wide viewports.
-->
