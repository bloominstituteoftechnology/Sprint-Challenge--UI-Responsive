1. If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?
   The `box3` class would have the most specificity weight.

2. Describe the difference between display: block; and display: inline;.
   `display: inline` places the element next to other elements on the same line as an inline element.
   `display: block` places the element on a new line as a block element that takes up the whole width.

3. While using flexbox, what axis are you using when you use the property: align-items: center?
  `align-items: center` centers items on the cross axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
   * Fixed layout: The size of the website is fixed and doesn't change. Very rigid.
   * Adaptive layout: The size of the website changes according to breakpoints. Better but still rigid.
   * Fluid layout: The website tries to adjust to any viewport size no matter how small or big--
     this can lead to some very strange results.
   * Responsive layout: A truly responsive website is a combination is adaptive when it needs to be and
     fluid when it needs to be; it is the best of both worlds.

5. Why do we need to use the CSS property max-width on the outer-most container in a responsive website?
   I'm still not sure on this one but I think the answer is that the outer-most container has to be set to a max width so that all of its descendants will be able to adjust accordingly.

   