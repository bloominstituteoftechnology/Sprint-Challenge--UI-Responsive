# Answers to the Self Study Questions

### `1. If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?`

- box3 would carry the most weight outranking the class names behind it.

### `2. Describe the difference between display: block; and display: inline;.`

- `display: inline` Displays an element as an inline element (like <span>). Any height and width properties will have no effect. `display: block` Displays an element as a block element (like <p>). It starts on a new line, and takes up the whole width.

### `3. While using flexbox, what axis are you using when you use the property: align-items: center?`

- The alignment is set on the x axis.

### `4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?`

- A fixed or static layout stays in its absolute position during resizing due to the use of px instead of more adaptive parameters.
- Adaptive layout means that there are several versions of the layout which are displayed based on the screen size of the viewer. Think of it as several fixed layout designs, layout A is displayed when the screen size is within size range N — NN.
- With fluid layout you specify sizes not in pixels, but in percentages. Meaning, if the screen size changes, the proportion of elements will stay the same.
- Responsive layouts will divide all possible screen sizes in ranges. The interface has slightly (or completely different) layout depending on the screen size it’s viewed on. Also, depending on the screen size, elements will stretch or shrink accordingly. Responsive layout provides a custom experience for whichever screen size it’s viewed on.

### `5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?`

- Using max-width will adapt to any screen size and keep your page responsive.