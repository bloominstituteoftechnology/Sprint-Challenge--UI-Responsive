#### If you saw this HTML: `div class="box box1 box2 box3"></div>` which class has the most specificity weight?

`box3` has the most specificity weight. To styling `box3`:
```
/* index.css */
.box .box1 .box2 .box3 {
	...
}
```

#### Describe the difference between `display: block;` and `display: inline;`

| Block                               | Inline                                								 |
| ----------------------------------- |----------------------------------------------------------------------|
| Element will have its parent's width| Element will have its content's width 								 |
| Margin and Padding is applicable    | Left/Right Margin and Padding is applicable							 |
| Width/Height is applicable          | Width/Height is Not applicable (should use padding to expand element)|
| Vertical-align is Not applicable    | Vertical-align is applicable                                         |

#### While using flexbox, what axis are you using when you use the property: `align-items: center`?

- `align-items` property targets cross axis
- Cross axis is the vertical line by default or when `flex-direction: row`
- Cross axis is the horizontal line when `flex-direction: column`

#### What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

- Fixed layout: all components remains theirs size across all devices. 
- Adaptive layout: some components have a fixed increased/decreased size (compare to their original size) for each devices
- Fluid layout: is a fixed layout with different scales for each devices
- Responsive layout: all components have a dependable size (as a percentage of their parents size)

#### Why do we need to use the CSS property max-width on the outter most container in a responsive website?

- `max-width` property allows the container to be flexible. Its width is in range of a certain value and below which allows the container to be fit to smaller screen devices    
- `max-width` property prevents an element to expand and create too much space between components especially with large screen devices  