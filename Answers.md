Questions: Self-Study

1. If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?
   As written these classes have the same specificity weight. How they are styled in the css could affect the weight, as in the css the last instruction has the highest weight. In css 'box box1 box2 box3' would have a specificity weight of 0,0,0,4 and would therefore have a higher weight than 'box box1 box2' with its weight of 0,0,0,3. 


2. Describe the difference between display: block; and display: inline;.
   The difference between 'display: block;' and 'display: inline;' is that 'display: block;' gives the element the maximum possible width and height that it was assigned, while 'display: inline;' has no width, height, or margins, and hugs the element to which it was assigned.


3. While using flexbox, what axis are you using when you use the property: align-items: center?
   The property 'align-items' uses the cross-axis and is the counterpart to 'justify-content' which uses the main axis.


4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
   A fixed layout does not change no matter the device and viewport size it is viewed on. The layout and element positioning and sizes are all the same. A fluid layout changes proportionately (using percentages) with the viewport size. Adaptive layouts go one step further and can add additional changes depending upon the device or other variables (using media queries). Finally, responsive design does the most and both scales in size and has layouts that change for different environments.


5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
   The max-width property on the outer-most container prevents elements from busting out of the designated area and thus introducing a scroll bar.
