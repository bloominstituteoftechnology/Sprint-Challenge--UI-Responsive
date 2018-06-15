<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight? 

Box3 because it's the last one. 



2. Describe the difference between `display: block;` and `display: inline;`.

The difference is display: block; forces a line break after a block element and has full width if it's not defined. It also doesn't allow elements to exist beside either side of it.

Display: inline; however lets elements reside beside on its left and right side and doesn't care about top and bottom paddings and margins, but it does care about top and bottom and the height and width. 

3. While using flexbox, what axis are you using when you use the property: `align-items: center`? 

Cross-axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?


Fixed layouts use fixed pixel widths but in the long run break when site visitors visit on different devices than what was intended during initial design, which is probably for desktop.

Adaptive is meant for devices by using media queries meant for them, but devices change dimensions overtime with different releases over the years and so many phones and tablets being released consistently creates viewport viewing issues. 

Fluid uses percentages but as browsers change, it can cause problems. Doesn't look great on big TVs and large desktops because percentages don't account for actual dimensions and pixels. 

Responsive uses media queries for all devices and desktops and laptops. They target general break points and scale elements of a page and wrap them so everything appears harmoniously. 

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?

Because you want the most real estate on a screen for the container that contains all the elements of your site so that way it creates a general sandbox for your audience's view in their viewport without it going beyond the maximum width specified so that way the elements don't start breaking apart. Then from there you could and would apply different media queries so that each element/section/inner container on your site can have its own breakpoints according to the device. 
