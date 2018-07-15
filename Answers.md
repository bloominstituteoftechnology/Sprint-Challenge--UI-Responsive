<!-- markdownlint-disable -->
# Sprint-Challenge - Week 01 - UI-Responsive

**1. If you saw this HTML:**

```html
<div class="box box1 box2 box3"></div>
```

**which class has the most specificity weight?**

ANSWER: 

It depends on which class appears last in the css file. 

  Example 1:

  ```css
  div .box1 {
      color: red
  }

  div .box2 {
      color: blue
  }
  ```

  Example 2:

```css
  div .box1 {
      color: blue
  }
  div .box2 {
      color: red
  }
```

In Example 1: div text would be blue. In the Example 2, div text would be red.

Codepen Example [link](https://codepen.io/cesarnml/pen/PBZOoE)

**2. Describe the difference between `display: block;` and `display: inline;`.**

- `display: block` ➡️ sets element to block-level. Block-level elements span all horizontal space available and begin on a new line.

- `display: inline` ➡️ inline elements horizontal span only the space required to contain the element and do not begin on new line


**3. While using flexbox, what axis are you using when you use the property: `align-items: center`?**

The `align-items` property selects the cross-axis. The cross-axis will be the y-axis if `flex-direction` is set to row or `row-reverse`. The cross-axis will be the x-axis if `flex-direction` is set to `column` or `column-reverse`.


**4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?**

Fixed layout uses fixed widths to determine container sizes and is not responsive to the user's viewport dimensions.

Adaptive layout uses media queries to optimize layout design based on the user's viewport dimensions, but each media query still employs fixed widths.

Fluid layout uses percent based widths and adaptive font-sizes (`rem`, `em`) to dynamically adjust content layout based on the user's viewport dimensions.

Responsive layout = Fluid + Adaptive layout. Responsive layout employs both media queries and percent based widths to dynamically optimize content layout based on the user's viewport. 


**5. Why do we need to use the CSS property `max-width` on the outer most container in a responsive website?**

The `max-width` setting on the outer most container keeps the website from spreading out beyond a set width if the user's viewport exceeds the max-width setting.