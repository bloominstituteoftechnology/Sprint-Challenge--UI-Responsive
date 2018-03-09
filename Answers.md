1. If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?

  Box 3, despite all of the boxes being in the same origin, Box 3 has the most weight due to being called last.

2. Describe the difference between display: block; and display: inline;.

  display:block provides the element with a maxed out width and is given it's own line.
  dispaly: inline only takes up as much width as it's corresponding element and stays within it's own line.

3. While using flexbox, what axis are you using when you use the property: align-items: center?

On the cross axis, however the actual direction can change depending on the value of flex:direction.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
  Fixed layouts has hard-coded size values and none of the elements will adjust.
  Adaptive layouts will fit itself to the user's screen resolution and moves various components within it to adjust for the screen using media queries.
  Fluid layouts primarily use percentages for the width values, giving easy scaling within it.
  Responsive layouts use media queries to change it's design and layout depending on the viewport size.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

  As all the other width values use percentages, it has to call on one base value to base off the percentages.
