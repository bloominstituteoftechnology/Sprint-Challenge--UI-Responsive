1) If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?

Answer: Box3 due to it being the last element with multilple decolarations that have equal specifity.  


2) Describe the difference between display: block; and display: inline;.

Answer: display: block has a bit of white space on top and bottom of it and expands to fill their parent and 100% of your screen. display: inline are just big enough to hold their children and will take up enough width accordingly. 

3) While using flexbox, what axis are you using when you use the property: align-items: center?

Answer: Cross axis


4) What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

Answer: 
Fixed layouts have fixed widths in px meaning the .container is being told not to move. (ie: viewing this layout on small screens will cause you to have the horizontal scroll bar at bottom of the page) which makes the site not as visually appealing. 

Adaptive layouts have the ability to resize the site based on the size screen you're viewing it on. This can only be achieved when you have the different versions of the layout design in your data (so the screen knows how to react when at different screen sizes).

Fluid layouts have specific sizes in percentages, not px. So if your screen size changes, the proportion of your website will fix accordingly. Not ideal for super small screens though as it can make it hard to read.

Responsive layouts have several breakpoints which sections out your screen sizes for various devices. This is probably my favorite layout (although time consuming) but I can see the appeal given what we've gone over this week that it's beneficial to have your site work and look great on all screen sizes/devices.


5) Why do we need to use the CSS property max-width on the outter most container in a responsive website?

Answer: Using max-width improves your browsers funtionality when viewing the webpage from small devices/screens and sets the max width your element can be. At end of the day this also ensures that your webpage isn't too wide on larger screens as it will constrain your content to it's canvas.