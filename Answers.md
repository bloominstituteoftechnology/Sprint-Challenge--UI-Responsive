1. It inherit from left to right, but will overwrite a css property on the rightmost.
2. Display block will make an element take up the entire width of the view. Display Inline on an element will make it so it only takes the space of its width.
3. Align items works on the cross axis of the flex container
4. A fixed layout does not take into consideration the users screens width. Adaptive will change at different widths. Fluid layouts change the size of elements for different screen sizes. Responsive uses media queries,percentages and rems to change the layout for different screen sizes.
5. You need the max-width on the container so that the layout can respond to different screen sizes in a particular media query.