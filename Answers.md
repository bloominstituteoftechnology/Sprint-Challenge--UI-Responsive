1.The weight depends on the last rule that is declared in the CSS.  If one element is directly targeted, that will take on those traits.  Otherwise they will take on the traits of its closest ancestor that has the declaration applied.  
2. An element with Display: block property will expand to fit in its parent container;including its height. Vertical-align is ignored. They will be placed below the previous element initially (without any rules applied).  If inserted, other elements will drop below.  Padding and margins can be applied to them. They are more or less structural elements.
Inline elements will act much like text.  They will not disrupt the flow of the content when inserted.  They only take up as much space as they have to. Height and width properties are ignored but can take on block properties if floated. The vertical-align property can be used.

3.  The cross axis.

4.Fixed layout has a set pixel width and will not adjust to screen size.  Fluid layout is configured by percentage and content will adjust proportionally to the screen size.  Addaptive layout will have several fixed settings for different screen sizes.  Responsive layout will utilize both fluid and adaptive traits and include breakpoints so the transition between screen sizes is smooth.  Elements can reposition themselves accoringly.

5. Responsive layouts utilize percentage based widths and any containers under that outermost container must be adjusted accordingly so they can live within it.  Max-width is set in pixels and equals 100% of the container. 