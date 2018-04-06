1.  If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?

When we have multiple CSS selectors match and they have he same specificity, order of selectors matters.  There are several rules about it and one of them is “rules that appear later in the code override earlier rules. 

So in this case, box3 has the most specificity weight.  

2. Describe the difference between display: block; and display: inline;.

Block and inline are the vault of display in Box model.  When [display: block] is applied, the element takes up the whole width of their container (or across the webpage from left to right) unless hight and width are assigned.  On the other hand, [display: inline] will take up as little space as possible, just cover its element.

3. While using flexbox, what axis are you using when you use the property: align-items: center?

This is one of the confusing topics when I got introduced into flexbox.  Any properties that set to “align-items, align-content or align-self”, the element will perform in “cross axis”.  So the answer is “Cross Axis” we use for [align-item: center].

Meanwhile, any properties with “justify-…”, the element will set in main axis.  

However, main and cross axis doesn’t mean x / y axis in mathematics or horizontal and vertical line.  It depends how [flex-direction] property is set.  If the direction is set as row [flex-direction: row;] which is also the default of [flex-direction], main axis will be horizontal and cross axis will be vertical.  But if [flex-direction: column;], the main axis will be vertical and cross axis will be horizontal. 

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

The difference between fixed, fluid, adaptive and responsive layout is;

Fixed layout - the layout is built by using hard codes which means developers assign certain values or fixed measurement to each properties for example .container { width: 880px; font-size: 16px;}.  So that the layout cannot react well or cannot react at all when the resolution of screen changed.  It is not user-friendly for the viewers because the website does not adapt to the screen size of the device they are using.

As the users matter the most today, here are layouts that can answer the user’s needs

Fluid layout - instead of using fixed number for values of width property, developers convert into percentage of space.  And also the developer still are able to keep certain element as fixed.  With the design, the user could be happier.  However, there are some disadvantages.  Some contents with a set width, image for example, cannot be adjust according to different screen resolution.  Also the element of the page may adjust accordingly which means it can be stretched in order to fill the big screen or crown up in the middle for the small one.

Adaptive layout - the user can be even more happier with adaptive layout.  The design is made in order to be able to view from different sizes of screen.  Adaptive websites adapt to the width of the browser at a specific points (breakpoints). Once the server detects the width that set in media queries [@media(max-width: breakpoint){ }], it adapts the layout and present the right version of the website to the users.  

Responsive layout - it’s quite similar to adaptive layout in term of user-friendly.  They both change appearances based on the user’s devices.  However, responsive design responds to the size of the browser at any given point.  This means all elements will be scaled according to the user’s devices.  (Font, images and layout are converted into percentage based on its parent element.)

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

Without max-width, website would be hard to read.  The responsive layout is designed to fit to any screen size.  If the user has a gigantic screen, the user would probably lose track and get confused which line of text they are reading.  In other word,  max-width is needed to set for responding appropriately with human peripheral vision.   
