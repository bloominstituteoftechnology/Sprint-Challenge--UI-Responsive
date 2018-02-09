If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?

.box3 would have the most specificity weight. If you declared the background of box, the later declared the background of box3, the background of box3 would change, but not box1, unless they're defining the exact same element(box.)

Describe the difference between display: block; and display: inline;.

display: block; tries to take up the full span of the page.
display: inline; only fills what's necessary to display properly.

While using flexbox, what axis are you using when you use the property: align-items: center?

The cross axis is what you are using when you use the property: align-items: center;

What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

A fixed layout is exact. it doesn't move or change regardless of viewport or device.
An adaptive layout is a little less exact than a fixed layout, with breakpoints pased on the viewport.
A fluid layout is solely based on the viewport and is buggy based on devices.
A responsive layout is a combination of fluid and adaptive - it moves and resizes when the viewport is changed.


Why do we need to use the CSS property max-width on the outter most container in a responsive website?

Because I was told to! Kidding, the max-width property will help aquire/maintain a ratio for percentages when the website has to be responsive. The outer-most container is chosen because we want everything in it to be relative to that max-width property.
