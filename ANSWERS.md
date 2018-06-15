<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
  box3 has the most specificity weight.
2. Describe the difference between `display: block;` and `display: inline;`.
  display:block is the default display for block elements, which we can use the box model on. display:inline is the default display for inline elements, ie elements that are in line with the text.
3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
  We are utilizing the cross axis when using `align-items:center`
4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
  Fixed: has a fixed width and does not adjust size based on platform or screen.
  Fluid: A percentage based layout that fills the screen no matter the platform or device size.
  Adaptive: A combination of fluid and fixed, changes view based on screen size, has breakpoints for changing views. Different templates for different devices.
  Responsive: Similar to adaptive, uses media queries to respond to screen size/platform, one template used for all devices and views.
5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
  To keep all content within the container within the size of the container, preventing individual elements from extending to the full width of the browser (ie, an img that extends 1000px while the rest of the page is within 800). Also allows for centering the site on the browser page (I believe?)
