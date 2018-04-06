# Spring Challenge: UI-Responsive

## Self-Study Questions

### 1. If you saw this HTML, `<div class="box box1 box2 box3"></div>`, which class has the most specificity weight?

The `box3` class would have the most specificity weight.

### 2. Describe the difference between `display: block;` and `display: inline;`.

#### `display: block;`

This property makes the element a block which will extend horizontally to the edges of the container/page. Each consecutive new `display:block;` item will be on a new line, regardless of how big or small the content inside is.

#### `display: inline;`

This property makes the element inline, which means that the size of the element will be only as large as it needs to be to fit the content inside. It will also other inline elements to be on the same line as it if space allows.

### 3. While using flexbox, what axis are you using when you use the property: align-items: center?

You are using **the cross axis** when using the property `align-items: center;`.

### 4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

#### Fixed Layout

A fixed layout is a layout based on absolute sizes. The unit of those sizes is usually the pixel. Nitpicky screen resolution details aside, a pixel is a pixel, so an element that is 100 pixels wide will be 100 pixels wide no matter the size of the device or screen. 

#### Adaptive Layout

An adaptive layout tends to use multiple fixed layouts that are then assigned to "breakpoints". A common breakpoint is the device width of the screen. This is more flexible than fixed, for it allows more customized layouts based on the screen or device dimensions.

#### Fluid Layout

A fluid layout doesn't rely on fixed values, but percentages. So instead of using pixels to determine size, a percentage relative to the dimensions of the viewport is used instead. This allows web pages to scale seamlessly from a wide gamut of dimensions.

#### Responsive Layout

A responsive layout is a mixture of both an adaptive layout and a fluid layout. It has the advantage of a fluid layout, but breakpoints allow for more customization of the flow and positioning of the layout for smaller screens and devices.

### 5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?

If a max-width is not defined, the percentage will be based off the size of the viewport. This can lead to comical situations, where elements are blown up to ridiculous sizes in very large resolutions and viewports.