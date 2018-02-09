1. box3
2. display: block elements start a new line and take up as much of the viewport on that line as they possibly can. 
   display: inline elements don't start a new line and take up as much space as is necessary to display their content.
3. cross-axis
4. Fixed layout - A fixed layout has a hard-coded pixel width that stays the same regardless of screen size. Not good when viewing a page designed for a desktop on a mobile phone for example. There will be miles of scroll bars.
   Adaptive layout - A fixed layout has multiple hard-coded versions of a page. Which version is displayed depends on the screen size of the viewer. If a page is purely adaptive it leads to a tedious coding process due to the vast amount of screen sizes available these days.
   Fluid layout - A fluid layout uses percentages, ems, and/or rems so that as viewport size gets larger or smaller the page elements expand or contract in proportion to the size of the viewport. Although this is really helpful it can lead to unreadable text and hard to view elements in general on really small screens because the elements can become too small.
   Responsive layout - Responsive layout takes the best aspects of fluid and adaptive layout and combines them. Elements shrink and grow in proportion to the page as in adaptive layout but multiple breakpoints are set using media queries that allow the page to be restrucured to fit multiple screen sizes without elements becoming too small to be functional or extremely large and ridiculous looking.
5. Setting the max-width property in the outer most container prevents the page from stretching to the edges of the screen in cases where a viewport may be very large. If a page stretches the content too far it could lead to a weird looking, hard to visually digest page with really long single-line paragraphs of text, images that are stretched far beyond what is visually appealing, and similar problems.

