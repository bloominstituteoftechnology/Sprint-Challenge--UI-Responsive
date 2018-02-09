1. I have researched a little bit about class ordering in the class attribute tag of html. From what I've read, class ordering does not matter when it comes to specificity in CSS. 

2. Block takes up the whole width of the page and adds a new line below it. Inline only takes up as much width as needed to display its content, padding, border, and margin.

3. If you use flexbox without changing the direction, the axis affected by align-items is the cross axis.

4. Fixed layout is static, and its widths, margins, paddings, etc are hard-coded into the application. This means that if the user's viewport changes the application does not modify its behavior. Fluid layout is more responsive than fixed, and I believe it uses a lot of floats and in-line blocks. The issue with this layout is that there can be white-space issues for different resolutions. Adaptive Layout is like Responsive layout, the main difference is that the server decides upon a CSS layout to send to the client's browser. In order to do this, the server must have a lot of different CSS layouts ready for differing resolutions. In contrast, responsive layout has only one CSS layout which uses media queries to decide upon which css styling to use. This means that only one CSS file is needed for the server to contain. This layout is also very responsive, because if a user has a device that can toggle between landscape and portrait, the CSS file can detect the toggle and adjust the css rules to apply.


5. We need max-width for the outer most container, because without it, the application will stretch too much on very large resolutions. This adds too much white space between elements, and it makes the application look worse than if a set max-width was applied.
