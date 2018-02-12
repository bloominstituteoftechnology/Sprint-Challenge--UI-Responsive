1.
    The div class box3 would have the most specificity weight. This is because it is designated in the most specific way: target ONLY the box3 that is inside a box2, that is inside a box1, that is inside a box.

2.
    Display: block will use the entire width of the page to display itself, regardless of content. Inline will only take up as much space as the content uses.

3.
    The "align-items" tag uses the cross axis inside of flexbox. This is by default the vertical axis, so align-items:center would align items vertically, by default.


4.
    Fixed layouts are websites that do not respond to different display mediums at all.

    To me, a fluid layout is where the size of the websites content changes continuously, i.e not along breakpoints.

    An adaptive layout is where you have several different layout versions that change depending on the screen size of the person viewing your website.

    A responsive layout is a combination of fluid and adaptive layouts. It's size changes continuously and it has several different styles for different sizes.


5.
    If we did not have a max-width on the outter most container, the page size would increase with larger and larger screens. It seems to me that this would cause the need to create needlessly extra breakpoints to account for extra large screens.
    
