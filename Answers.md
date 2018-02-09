1. Box3 has the most specificity weight because it is the declared class that is furthest to the right. 

2. Display block makes an element take up the entire width of the screen and get it owns line, unless forced to behave otherwise using float. An inline element is an element that only takes up as much space as it's content requires, and does not start a new line. 

3. Align-items refers to the cross-axis whereas justify-content refers to the main axis. So in flex-direction: row (the default) align-items would affect the items vertically, but in flex-direction: column align-items would affect them horizontally. 

4. Fixed Layout: A fxed layout is a layout that has a fixed width that never changes. If the screen is smaller than this width, a horizontal scrollbar appears. Everything is coded in hard px. 

Adaptive layout: This is essentially a collection of fixed layouts that change depending on screen size. As the screen passes a media query cutoff, the layout morphs into a more appropriate sized (but still fixed) layout of the site. There are still horizontal scroll bars on screen widths in between those breakpoints. 

Fluid: A fluid layout uses percentages to try to adjust content for smaller screens. As the screen width decreases, the element widths in the page decrease, but the layout remains the same. This often results in very small elements and columns. 

Responsive Layout: A responsive layout is one that combines the best parts of adaptive and fluid layouts. There is a collection of layouts for various breakpoints, but those layouts are coded using percentages. As the screen size decreases, the content shrinks to fit until it hits a breakpoint, then the layout rearranges and the content continues shrinking to fit until the next breakpoint. There should never be a horizontal scroll bar on a responsive site. 
