1. If you saw this HTML: ```<div class="box box1 box2 box3"></div>``` which class has the most specificity weight?
 
Answer: Box


2. Describe the difference between ```display: block;``` and ```display: inline;```.

Answer: ```display: block;``` takes up a defined static area of space that spans the width of the containing area. ```display: inline;``` only takes up the height and width of the contained text.

3. While using flexbox, what axis are you using when you use the property: ```align-items: center```?

Answer:```align-items: center``` centers the flex item/'s in a vertical layout. 

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

Answer: fixed layout is immutable from its native screen/viewport size.
adaptive layout can change to fit various viewport sizes but depends on pre set viewport sizes, so can may not work on all obscure screen sizes.Fluid layout allows the web site to adjust on the fly depending on size of screen and some items may stay fixed as well. Responsive layouts has the same properties of a fluid layout but is more optimized as there is only one master layout.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website? 

Answer: Otherwise the layout will stretch to fit extreme screen sizes and distort the webpage with ``` max-width``` you can contain the layout in a defined space to prrevent it blowing out.