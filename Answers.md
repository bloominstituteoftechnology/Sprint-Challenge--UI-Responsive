1. box3 has more specificity weight.

2. display: block, takes the whole space on that line, regardless of how much space it actually needs.
2... display: inline, only takes as much space as it needs.

3. align-items uses the cross-axis (align-? means cross axis, main-? means main axis).

4. Fixed layout looks the same when the window size changes, the pixel width is constant, all items pixels remain constant (contant's width doesn't stretch or shrink).
4.. Adaptive layout has some media breakpoints that make the layout change at a specified width. The layout is usually at media breakpoints for desktop, tablet, or mobile. The width is still a constant pixel for each break point (content remains the same width in pixels, until it reaches a breakpoint).
4...& 5 Fluid layout has widths that are not a constant pixel width, the widths are a percentage of the parent body width. The parent body has a maximum width, and the children elements have a percentage of width that references the maximum width of the parent. As the window size changes, the content size changes. We need a max width on the most outer element to create a percentage for the children elements.
4.... Responsive layout combines both Adaptive layout and fluid layout.

