<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
  depends on where they are located on the style sheet as well, but `box 3` would have the most specificity weight here. 


2. Describe the difference between `display: block;` and `display: inline;`.
  `display: block` makes inline/inline-block elements to block elements, so now the element will behave as a block element would, taking up the full width if no width specified, they also behave different when positioning them


  `display: inline` makes block/inline-block elements to inline elements, so now the element will behave as an inline element would, it would only take up the space necessary for the element content, it will not skip a line like block elements, you can put multiple inline elements in one line 


3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
  align-items is always for the cross axis, regardless of whether you are using rows or columns


4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
  `fixed layouts` - are websites that are just that, fixed, not responsive, contained to one size
  `adaptive layout` - these websites adapt to devices through media queries/breakpoints
  `fluid layout` - fluid is similar to adaptive layouts but instead of breakpoints, these websites use repsonsive units to flow with the size of the viewport, they do not include design changes based on breakpoints though so they can get funky the too big/too small screen sizes
  `responsive layout` - these websites are best of both worlds, they are fluid and also adaptive, so they flow with the size of the screen, and also change design at certain breakpoints for most of the different devices/screen sizes out there


5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
  that will contain everything else, and if you use responsive units, the content will follow the container as it gets smaller, and will stay within the container as it hits the max-width and the viewport gets bigger

