1. If you saw this HTML: ```<div class="box box1 box2 box3"></div>``` which class has the most specificity weight?
1 Answer:  div .box .box1, meaning the selector + as many .class as identified.

2. Describe the difference between ```display: block;``` and ```display: inline;```.
2A:  display:block forces an html element to become a block with a width equal to its parent. display:inline forces an html element to only use the width of the content of the element. 

3. While using flexbox, what axis are you using when you use the property: ```align-items: center```?
3A: cross axis

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
4A: 
-Fixed layout: html elements are assigned a static width value, which can be problematic if the screen's horizontal size is changed.
-Adaptive: has viewport metatag & media queries that allow a Fixed layout to change at designated breakpoints
-Fluid: html element widths are aassigned percentage values which allow the elements to resize as the screen's horizontal size is changed.
-Responsive: is the combination of Adaptive & Fluid. html element widths will have percentage widths that allow them to smoothly resize as screen's horizontal size is changed.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
5A: max-width property constrains the container from expanding farther than desired if the screen's horizontal size is changed. When assigned to the container, it ensures none of the html elements extend beyond the edges of the container & therefore the screen. 