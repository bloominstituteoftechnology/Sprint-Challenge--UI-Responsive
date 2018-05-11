<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?

  box3 has the most specificity weight since it's last in the list. CSS is fond
  of the last element, I think with the idea in mind that the later the tag,
  the more recent the styling, and thus more important.

2. Describe the difference between `display: block;` and `display: inline;`.

  display: block; styles an element to where it's styling block takes up the
  whole width of the screen. display:inline; styles an element so that other
  elements can be placed on either side of it, and it only takes up roughly
  the size of the element itself.
3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
  align-items: center is handling items on the cross axis

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
  fixed layout: Item sizes are hard coded in, lots of scroll bars, non-responsive
  adaptive layout: When we code a whole new page specifically for a certain screen
                    width. Works for desktops, phones, etc, but is not very responsive
                    for widths in between hard coded values, and can't account for
                    new, oddly sized devices
  fluid layout: everything coded with percents, scales well (up to a point) after
                which thiings become distorted and difficult to read.
  responsive layout: The holy grail of design, account for various screen sizes with
                      media queries, flexibly scales with percentages and just
                      overall looks tasty.
5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

    Because the outer container is the parent container of the entire web page.
    All our little html children will inherit from this parent, and thus will
    more or less stay in the width laid out by the parent container. 
