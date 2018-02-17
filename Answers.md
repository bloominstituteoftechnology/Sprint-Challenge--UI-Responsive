# Answers to Sprint Challenge - UI Responsive

## 1.) If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?

The class that has the most specificity weight would be `box3` because it was the last class applied to the `div` which will overwrite any existing CSS properties.

--------------------------------------------------------------------------------

## 2.) Describe the difference between `display: block;` and `display: inline;`.

The difference between `block` and `inline` is that `block` will display the object in a block that takes up the entire width of the viewport, unless width is specified. Any following objects will be moved to the next line. With `inline` the object falls onto the same line as the rest of the content. Certain properties are disabled with `inline` such as width.

--------------------------------------------------------------------------------

## 3.) While using flexbox, what axis are you using when you use the property: `align-items: center`?

The cross-axis

--------------------------------------------------------------------------------

## 4.) What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

- **FIXED LAYOUT** - The viewport and DOM objects are set to fixed dimensions, with no ability to scale or flow based on the device or viewport size. All elements display exactly the same on all sizes of screen or zoom.
- **ADAPTIVE LAYOUT** - This type of layout does not have one specific design or layout, instead it has multiple designs/layouts depending on the number of media queries in the CSS file. The layout will change based on the overall width of the viewport, corresponding to the media queries.
- **FLUID LAYOUT** - A fluid layout is percentage based with little to no fixed pixel dimensions. It has the ability to grow and shrink to size based of the viewport size. Most DOM elements do not grow/shrink, instead they mearly gain or lose additional width (i.e. font is still the same pixel size but the surrounding box is now wider).
- **RESPONSIVE LAYOUT** - A truely responsive design takes all factors into account and the layout _and_ design will respond in direct proportion to the viewport. This means that as the screen size gets smaller, the font size will increase and extra "filler" design objects may be hidden for ease of use and reading. The layout is often elongated and vertical scrolling is preferred.

--------------------------------------------------------------------------------

## 5.) Why do we need to use the CSS property max-width on the outter most container in a responsive website?

The outer most container serves as a "ruler" or guideline for the responsive action to take place. If the browser's viewport is greater than the max-width, then the container will resize to the next largest media query that fits the rule. Without the max-width property, the page will not respond correctly when resized or viewed on a smaller/larger device.
