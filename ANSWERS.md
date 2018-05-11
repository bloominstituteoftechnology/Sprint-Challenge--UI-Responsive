<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
 I'm a little confused by the question. but I think the specificity would be either furthest to the right, or in how it is called. For example #box3 would be the most specific.


2. Describe the difference between `display: block;` and `display: inline;`.

Display: block; extends the element to take up the entire width.

Display: inline-block;  puts the elements side by side along the same axis, to 'fill/smash' the width.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?

Cross Axis

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

fixed layout: has a desginated 'hard' defined width that does not adjust to browser reshaping. Can create a poor user interaction because a scroll bar will be necessary to view content as it will be 'fixed' off screen many times.

Adaptive Lay-out :     this is a layout pre-determined with the viewer window in mind. so elements box models will be reconfigured in relation to viewport constraint.


Fluid: The elements take up a percentage of screen real-estate. So this means that as the viewport reshapes, elements will shrink or expand in relation to the fixed percentage share of the container.

this has advantages but can really can present some extreme reconfigurations that inhibit user experience.

Responsive:

is something of a combination between fluid and adaptive. Pre-determined Breakpoints, deisgnated in media queries can all css styling for specific viewports and we can combine a mix of percentage based elements as well as adaptive type reconfigurations.



5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

This allows us to have a value from which we can do math to employ rem calc's. and by setting font-size to 62.5%   px / max-width = making 1rem = 10 px.
