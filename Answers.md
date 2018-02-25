
1. "If you saw this HTML: ```<div class="box box1 box2 box3"></div>``` which class has the most specificity weight?"

A: The furthest to the right has the highest specificity.

2. "Describe the difference between ```display: block;``` and ```display: inline;```."

A: An in-line element would respect surrounding elements and try to fit in with how they flow, while a block element would try to expand as far as possible horizontally, potentially pushing other elements out of its way.

3. "While using flexbox, what axis are you using when you use the property: ```align-items: center```?"

A: The cross-axis, or in other words, the opposite of the axis declared by the flow-direction property. By default, flow-direction is set to row, which would make the column or y-axis its opposite.

4. "What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?"

A: A fixed layout does not account for a change in screen size, while a fluid layout does. With adaptive web design, you target several specific screen sizes using fixed layouts, basically creating several separate designs. In responsive web design, you create one presentation and use media queries to make specific enhancements to the original depending on the current screen resolution.

5. "Why do we need to use the CSS property max-width on the outter most container in a responsive website?"

A: You use max-width because a responsive site will try to adapt to really large resolutions by using lots of white space between elements, which can actually make accessibility worse. Putting a ceiling on the scaling keeps the site readable no matter how absurd the resolution becomes.
