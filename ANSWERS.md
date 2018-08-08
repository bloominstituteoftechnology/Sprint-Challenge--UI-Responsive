<!-- Answers to the Self Study Questions go here -->

_Question_

1.  If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class
    has the most specificity weight?

_Answer_

- The HTML element has multiple classes of equal specificity when used
  individually to select.
- However the final style that would be applied to the `div` would be from the
  selector that comes later in the css file.
- Exception: If there is a css rule that selects the multiple classes together
  like `.box.box1` then that style will override any individual class selector.
  Of course the more the number of classes selected in the selector, the more
  the specificity irrespective of where it appears in the css file.

_Question_

2.  Describe the difference between `display: block;` and `display: inline;`.

_Answer_

- A block element would take up all the horizontal space "blocking" an entire
  line on the page. Examples inlcude `div`, `h1`, `p`, `section` etc.
- An inline element, on the other hand, would only take up as much space that is
  needed i.e. its width is restrictred to the content plus any horizontal
  padding. Examples include `a`, `img`, `span` etc.
- Another key difference between block elements and inline elements is that
  block elements may have a specific width and height, specific padding and
  margins. But an inline element cannot have vertical padding or margins. They
  may, however, have a horizontal padding or margin.

_Question_

3.  While using flexbox, what axis are you using when you use the property:
    `align-items: center`?

_Answer_

- Align items adjusts the position of flex items along the _cross_ axis.

_Question_

4.  What is the difference between fixed layout, adaptive layout, fluid layout,
    and responsive layout?

_Answer_

- A fixed layout is one that doesn't change irresepctive of the viewport width.
  If the viewport width is not enough to contain the page then by default the
  `overflow` is set to scroll behavior i.e. a horizontal scrollbar would appear.
- An adaptive layout layout changes its layout to adapt to the viewport width at
  specific breakpoints. It "snaps" to a lower/higher width when it hits the
  breakpoint. But still there are in-between points where the overflow would be
  scrolled.
- A fluid layout has a width set to be a percentage of the viewport width,
  creating a seamless transition when the viewport width changes as opposed to
  adaptive layout "snapping" in to place. In this layout you would never see a
  scrolled layout however, the elements don't squeeze beyond the width of their
  contents and when the viewports expand the layout keeps infinitely expanding.
- A responsive layout is a combination of fluid and adaptive layouts in that you
  never encounter an overflow like a fluid layout (seamless transition) and the
  layout "responds" to the viewport width, like the adaptive layout, at
  different breakpoints. All the horizontal width dimensions are in percentages
  and the layout itself changes at various breakpoints.

_Question_

5.  Why do we need to use the CSS property max-width on the outer most container
    in a responsive website?

_Answer_

- By setting the `max-width` to the outermost container we can set the width of
  all its descendants to be a percentage of the container's width.
- What this means is that the container becomes a single source of truth for all
  the width dimensions for the elements in the page.
- This makes the entire css design to respond to any changes made to the global
  container element.
