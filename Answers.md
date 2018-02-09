## Questions - Self Study - You can exercise your Google-Fu for this and any other _Sprint Challenge_ in the future. Remember to record your answers in _Answers.md_

1. If you saw this HTML: ```<div class="box box1 box2 box3"></div>``` which class has the most specificity weight?

   box3

2. Describe the difference between ```display: block;``` and ```display: inline;```.

   display:block is like a normal html element: nav ul li displays vertical. display:inline tries to put all the html elements on the same line: nav ul li displays horizontal.


3. While using flexbox, what axis are you using when you use the property: 
```align-items: center```?

   align-items: uses the cross axis, justify-content: uses the main axis. 


4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

   Fixed Layout: has 1 look or layout that will never change due to window size or device used to access it. not very easy to use, especially when accessing the site from a device that the fixed site wasn't intended for. 
   Adaptive Layout:  the layout of the page will change depending on the screen size, rearranging the location of objects on the page.
   Fluid Layout:   all widths are set to a percentage of the screen size, which can be difficult to scale down and up for all sizes. 
   Responsive Layout: best layout, uses media queries to make the same layout scale up and down for all screen sizes.


5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?

  max-width on the outer container makes the site stop expanding when the screen reaches a certain size, so if the user has a 2k or 4k screen and maximizes it, the main content area will stay in the user's focus. 


