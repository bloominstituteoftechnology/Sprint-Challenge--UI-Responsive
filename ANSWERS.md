<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
  Box 3 is the most specific due to being the last box class specified.
2. Describe the difference between `display: block;` and `display: inline;`.
display: block will place boxes on separate lines as the block will automatically take up an entire length, display: inline allows them to exist on the same width if the proportions are set within 100%.
3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
cross axis
4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
Fixed layouts are stagnant and do not adjust to different screens, making it difficult on many users to effectively interact with.  Adaptive layouts adjust to specified screen widths to remain ideal for users on different platforms.  Fluid layouts allow percentage width of its components, which can adjust to different user screen resolutions while retaining fixed components if necessary.  Responsive layouts are the most flexible and adaptive, loading faster due to having one master layout, though they are also the most tedious for designers.
5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
It allows for percentage-based width, margin and padding adjustments in child classes/selectors which makes it easier to get objects/text precisely where you want them.
