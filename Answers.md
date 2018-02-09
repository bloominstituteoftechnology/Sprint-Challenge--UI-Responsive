
1. .box3 would have the most specificity weight.

2. display: block; will take up the full width available and creates a new line before & after.
   display: inline;  will take up only the width that is needed and does not create new lines.

3. align-items: center uses the cross axis.

4. Fixed Layout - aka Static. The container does not move. The width stays the same regardless of           screen size or resolution. No longer used in modern web design.

    Adaptive Layout - There are different versions of the layout depending on screen size. Each new layout is in essence, a new fixed layout.

    Fluid Layout - aka Liquid. Sizes are specified in percentages, not pixels. As the screen size changes, the proportion of all elements stay relative to each other.

    Responsive - best for modern design. Several breakpoints exists which divide all viewport sizes in a range. It's a custom experience for each different device size. @media is used to make adjustments in CSS

5. If we don't use max-width, the content will keep expanding with the size of the viewport /               resolution. Not only will your design be 'ugly' & non-user friendly, but the text will be           impossible to read as per research.