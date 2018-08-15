### Answers to Sprint-Challenge--UI-Responsive</title>

1. If you saw this HTML: ```<div class="box box1 box2 box3"></div>``` which class has the most specificity weight? 

# Box3 has the most specificity as it is the furthest to the right.

2. Describe the difference between ```display: block;``` and ```display: inline;```.

# Block shows us blocks on the page in a column order. They refer to individual blocks that take up the width of the page on each line that they occupy. Inline-block can control how we configure that column of blocks, specifically by placing them horizontal across a page -- or 'in line.' Get it?! 

3. While using flexbox, what axis are you using when you use the property: ```align-items: center```?

# The cross axis is what is being used when we use the 'align-items' property. If we are in a column, the cross axis becomes horizontal rather than vertical while we are in a row.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

# A fixed layout is made with 'stiff' settings that don't adjust to new dimensions. An adaptive layout uses @media queries to adapt to new resolutions so that everything adjusts for the specific device that the layout is being viewed on. A fluid layout uses percentages to scale the resolution smoothly across devices. A responsive layout is a combination of fluid and adaptive. They tend to be percentage-based using rems for font so that they adjust without 'breaking' or looking awkward for the viewer.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

# The max-width property is setting the boundaries for the screen-size. When we create a webpage, the page is typically going to be smaller than the max-width, but the max-width acts a constraint that tells us when we've gone beyond the size of the screen.
