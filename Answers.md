1. box3

2. display:block takes up the entire space only limited by the width of the container it is located in, preventing any other object to share that line.            display:inline however tries to take up as little space as possible and can cause objects to overlap and collapse on each other when used incorrectly.

3. align-items: center affects the cross-axis.

4. fixed layout is hardcoded with px and so is unfriendly to various screen sizes.     adaptive layout has breakpoints at which the site will change in order to present itself differently on desktops vs tablets vs mobiles (still uses pixels).      fluid layout has no breakpoints and instead uses %s instead of pixels, thus allowing it to change and present itself according to the size of the screen. however there are issues at certain screen sizes where images will go off screen.      responsive layout uses both breakpoints and %s so that it can change layouts to present the site differently depending on the device used (ie desktop vs tablet vs phone) but also not be restricted to strict display sizes. Also has improved accessibility (ie for people with vision impairment)

5. max-width is used to so there is no priority issue with the width:100% statement that would have collisions otherwise. It also helps have a value for child classes to base their %s off of.