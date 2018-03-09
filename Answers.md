1. I believe they all have same specificity but the last one would take effect due to rule of cascading.

2. Display block turns element to act as a block, hence always taking new line and whole width. Display inline-block combines inline and block. The element acts as an inline element (not taking new line and whole width) but it is possible to apply custom width and height to it.

3. Criss Axis

4. Fixed layout is when everything is 'static' and measured in pixels. The layout will not change under any conditions.

Adaptive Layout introduces 'break points' that allow to tweak behavior based on current device or browser width.

Fluit Layout introduces percentage based measurements which allows for elements to keep their current position, margins and size based on browser's width or device's width.

Responsive layout combines adaptive and fluid layout introducing percentage based measurements along with break points to customize layout.

5. We need percents to base on something, that way we can specify pixels on parent container and use it for our percentage values. Max-width also allows us to control how element will behave if it has not enough space or too much free space.