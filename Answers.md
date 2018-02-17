## Answers

1. If you saw this HTML: ```<div class="box box1 box2 box3"></div>``` which class has the most specificity weight?
* The left most ("box") class has the most specificity weight.

2. Describe the difference between ```display: block;``` and ```display: inline;```.
* Block has whitespace above and below it, and no items next to it on the same line.  Inline will display on the same line within a block, with no whitespace (unless explicitly specified).

3. While using flexbox, what axis are you using when you use the property: ```align-items: center```?
* The cross axis.  Justify-content uses the main axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
* Fixed - aka static layouts have a fixed width in pixels.  The container of the site is programmed to not move.  Its width will stay the same no matter the view portal.  Resizing your browser window to less than the fixed container width will result in horizontal scrolling, which impacts UX and functionality.  Gives full control over how the site looks, but is generally not used because of poor UX and functionality.
* Adaptive - We create several versions of the layout to be displayed based on viewer portal size.  We created as several "fixed" layout designs and display them based on portal size so we have control over the UX.  Loading times are fast with these fixed layouts.
* Fluid - specifies widths in percentages (vs pixels), so your site will adjust to view portal changes.  The drawback is when the portal is resized to very small, it will condense your text and photos.
* Responsive - This is best practice, combining fluid and adaptive.  We define breakpoints, which divide portal sizes into ranges (e.g. mobile, tablet, desktop).  Depending on the screen size, elements will stretch or shrink accordingly because we have incorporated fluid design (percentages vs pixes).  Responsive layout provides a custom experience for whichever screen size it’s viewed on.  More design and testing effort is required for responsive than for adaptive layouts.

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
* Because the content will stretch all the way across the screen for large view portals and make it very difficult to read.  It allows for more control by the designer, so that exactly what is intended is seen.  I'm not entirely sure why this is needed in addition to the break points?  Are some browsers not compatible with media queries?