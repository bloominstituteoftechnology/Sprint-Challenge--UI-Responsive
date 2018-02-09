### 1st Sprint-Challenge: UI-Responsive

1. If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?

    * box3, as it is furthest to the right, thus read last, it will have the most specificity weight.  To be honest, I am
    a little confused about this subject area -- css classes and how they relate to index.html.

2. Describe the difference between display: block; and display: inline;.

    * `display: block` elements force a line break after each element, so they tend to render (unless you use float) as a
    column.
    * `display: inline` elements can be adjusted left and right for margins and padding, but not top and bottom.  Inline
    elements cannot have width and height set, but the computer will try to set elements next to one another.
    Unlike with flex-wrap, if an element does not fit on one line, it will be cut in half, the first half
    rendered to the top line, and the second half rendered to the line below.  This issue is partially addressed with
    `display: inline-block`.
    
3. While using flexbox, what axis are you using when you use the property: align-items: center?
    *`align-items: center` adjusts the cross-axis however, it is important when using flex to carefully examine your
    code to ensure you know whether the cross-axis is in fact on the vertical plain.  For example, if you are using
    `flex-direction: column`, then you will be using `align items` to adjust the elements along the horizontal
    cross-axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
    *`fixed layout` is the most rigid and not responsive at all.  The page will render such that all images, fonts,
    and elements remain fixed, and are not effected at all by adjusting the window size.
    *`fluid layout` is based on the viewport size of 100%.  This is somewhat more resposive compared with `fixed layout`
    ; however, you still end up running into a lot of issues related to readability in smaller windows, and excessive
    white space in the larger window sizes.
    *`adaptive layout` has specific breakpoints set for specific screen sizes (e.g. media queries for @laptop, @tablet,
    @phone); however, with the wide variety of screen sizes, a truly responsive layout at all window sizes is really
    needed.
    *`responsive layout` combines percent based `fluid layout` for responsiveness between `adaptive layout` breakpoints set
    for perfectly readable layouts at all the most commonly used screen sizes. rem/em/vw unit based font-sizes are also impemented
    so that the font-size is also responsive along with the rest of the web-site content.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
    *You need to use the CSS property max-width on the outter most container of a responsive website in order to center the webpage
    content with some white space on either side.  If you do not have a max-width container, then the container will fill the <body>
    by default, which is much less readable.