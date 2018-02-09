1 - If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?
- Considering class weights go from left to right in HTML, the specificity weight would fall on "Box".

2 - Describe the difference between display: block; and display: inline;.
- Display: Block will try to take up all the width available to it, while inline will try to take as little as possible.

3 -While using flexbox, what axis are you using when you use the property: align-items: center?
- The vertical cross axis! Unless you are doing it by column higher up, then it would be the horizontal cross axis.

4 - What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
- A fixed layout is very rigid, where the elements all have fixed positions within their container, usually done with exact pixel sizes.
- Adaptive layout would be the same as adding @media {} to your CSS for different break points, in essence giving a different overall website for different defined viewports.
- Fluid layouts are almost all % of container based, with a max-width set to your outer most container. This gives the page and it's elements the ability to flex and move with an ever changing viewport.
- Responsive is more or less a mixture of all of the above, where the website has @media {} breakpoints for defined viewports, but a smooth transition between maximum container with and the absolute smallest possible screen size. With a responsive layout you should never see a horizontal scrollbar except for extreme cases.

5 - Why do we need to use the CSS property max-width on the outer most container in a responsive website?
- This sets a baseline value for the rest of the container items. In other words, it constrains the fluidity of the other items within itself.
