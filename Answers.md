1. box3
2. Block elements take up the full available width, and inline elements only take up the amount of width necessary to present the data that they contain
3. cross axis
4. fixed - doesn't change with the screen size
adaptive - several layout designs are impletemented, so that as the screen width decreases, there are multiple stages of layout change, but no fluidity in between
fluid - as screen width gets lower than max-width of container, everything just kind of shrinks down to fit, even if those three columns of text get down to five words per line each
responsive - a combination of adaptive and fluid approaches that allows continuous decrease of screen-width to be met with readable, good-looking layout
5. We need max-width on the outermost container because otherwise the container will continue to grow past a point where the layout is still coherent.