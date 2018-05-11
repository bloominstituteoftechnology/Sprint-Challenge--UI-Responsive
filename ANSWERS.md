<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?

.box.box1.box2.box3. If they are nested, .box .box1 .box2 .box3; box 3 would have the most specificity weight.

2. Describe the difference between `display: block;` and `display: inline;`.
display: block, streches, or takes up the entire width of the container, display: inline does not, it is

within a block

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?

it is accessing the cross axis, anything with align is cross axis, justify would be main

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

fixed layout means there are no point breaks and no percentage based inputs in the code, or at least none that
affects the layout, the display is fixed, as in the display hax a fixed width of pixels and the website is static,
drawback would be when viewing on smaller screens, a horizontal scrollbar
adaptive has break points but is not percentage based, this allows for a better user experience but because it is
not percentage based there is a short coming in that it does may not look ideal in some display formats, there may be
gaps or other unpleasing visuals
fluid layouts are percentage based inputs and not pixel based, this means proportions of the elements will stay the
same, however it does not affect breakpoints, meaning on smaller screens, things can become very narrow, and
squished
responsive layouts are the best of both worlds from adaptive and fluid, it has breakpoints and percentage based
inputs so it looks the best on various display screens

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
percentages, it allows everything to sub divide nicely in every form of display layout, it allows for every
element to be within the container, and allows percentages to dictate where and how the specific element will
be viewed
