<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
- Box 3 has the most specificity weight because it is the last one on the list in the order of selectors. 
2. Describe the difference between `display: block;` and `display: inline;`.
-Display block means the browser does not put anything beside the element, it has it's own line. The only way two block elements can be next to each other is if you specifiy special styling. Inline elements do not have their own line, and will sit next to each other on the line as a default property. 
3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
- The cross axis. 
4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
-Fixed - Also known as static layout. The width of the top container stays the same regardless of screen size or resolution of the device the website is being viewed on. 
-Adaptive - There are more than one version of the dimensions of the page dependent on the screen size of the device the page is being viewed on. Computer vs. tablet vs. phone. There is a max width set for each of those devices, and the screen will change dependent on that. 
-Fluid - Size is specified in percentages NOT pixels. This allows the proportions of each element on the page to stay the same as the screen sizes changes. 
-Responsive - Responsive websites are a mix of fluid and adaptive. They use breakpoints to create an optimized page for a screen size range. The layout can be very different for each screen size range. Also, as in fluid design, the elemenents will shrink and stretch dependent on screen size. 

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
- For the integrity of the elements on the page to remain. Max width ensures the elements won't be stretched or skewed too much at a different screen size, and look awful.  
