<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
2. Describe the difference between `display: block;` and `display: inline;`.
3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?

  Answers
1. Class box has the most specificity weight.
2. When using `display: block`, the item fills the width of the screen. New items will appear below the previous item. This is the default in regular CSS. When using `display: inline`, the item takes up the least amount of room possible and items will appear next to each other.
3. In flexbox, `align` always refers to the cross axis and it may be vertical or horizontal, as it is perpendicular to the main axis which can change based on things like `flex-direction`.
4. Fixed v adaptive v fluid v responsive
    
    a. Fixed layout: the widths are fixed, so nothing changes when the viewport is resized.

    b. Adaptive layout: breakpoints are used to cause changes based on the viewport, but there are a limited number of views (typically 3: desktop, tablet, mobile) and the website doesn't change except for those views.

    c. Fluid layout: Every change in viewport size causes a change/resize in the view.

    d. Responsive layout: A combination of fluid and adaptive. There are set layouts for say desktop, tablet, and mobile. However, if the desktop viewport is bigger than the viewport size needed to trigger the desktop/tablet/mobile layout, the items all expand/shrink accordingly as the viewport is resized (unless expanded/shrunk into a different device's range, when the layout will then change to match what was coded for that device).
5. Studies have shown that ~500px is the max comfortable reading width on a website and designers like it when their designs work on all monitors, so we need some constraints on width. `max-width` is used so there is still control over how the website looks, even on hugely wide monitors like Josh's :) It is also the baseline for calculating the `width` percentages which make the website responsive.