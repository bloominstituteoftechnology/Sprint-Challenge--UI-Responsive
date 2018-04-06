1. If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?
A: In this div the class .box.box3 has the most specificity weight.

2. Describe the difference between ```display: block;``` and ```display: inline;```.
A: With display:block the element will want to take up the entire width of the container it is in (the width of the screen), whereas display:inline will only want to take up the space that it needs based on the content. This will allow other elements to come up next to them if they are also inline.

3. While using flexbox, what axis are you using when you use the property: ```align-items: center```?
A: Align-items is targeting the cross-axis. So depending on what your flex-direction has set as the main axis align-items will manipulate the cross-axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
A: 
- Fixed layouts have widths that are fixed and that we tell the layout to always have (hard-coded).
- Adaptive layouts are based on breakpoints and adjust their widths accordingly.
- Fluid layouts are percent based layouts.
- Responsive layouts incorporate both breakpoints and percent based layouts to provide a fully responsive experience.

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
A: It provides a constraint telling the container to not get bigger than the limit so that the page can use percent based layouts and adjust to different resolutions and screen sizes with the content fitting nicely inside our parameter.