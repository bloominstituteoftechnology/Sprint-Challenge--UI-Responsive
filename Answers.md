1. box

2. display:block makes it so that each item takes up as much space as its container, unless otherwise specified. display:inline acts like a sentence, where the container takes up only as much space as the content, so multiple other items may wrap around it.

3. Cross Axis

4. - Fixed is a static website, the page does not adapt when the window is resized.
- Fluid uses percents on the width, to adjust the page's components when the width of the window is resized, yet does not dynamically alter the design.
- Adaptive has preset page designs based on the size of the window/device viewing the page. 
- Responsive dynamically adapts it's design based on whatever window/device size.


5. You need to use the CSS property max-width on the outer most container in a responsive design because we need to ensure that the design maintains a certain aesthetic, and not setting this property would allow the design to stretch far too wide on large monitors.