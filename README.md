# advanced_css_sass_with_flexbox_grid_animations
My progress in the udemy course https://www.udemy.com/course/advanced-css-and-sass/

## Reference Links:

🧠 [Animation CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/animation)

- 🧠 [Animation Delay](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-delay)

- 🧠 [animation-iteration-count](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-iteration-count)

- 🧠 [Animation fill mode](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-fill-mode)

🧠 [Backface Visibility](https://developer.mozilla.org/en-US/docs/Web/CSS/backface-visibility)

🧠 [Box-shadow](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow)

🧠 [Transitions](https://developer.mozilla.org/en-US/docs/Web/CSS/transition)

🧠 [Background Clip](https://developer.mozilla.org/en-US/docs/Web/CSS/background-clip)

🧠 [Outline: border in box](https://developer.mozilla.org/en-US/docs/Web/CSS/outline)

🧠 [Outline-offset: sets the amount of space between an outline and the edge or border of an element.](https://developer.mozilla.org/en-US/docs/Web/CSS/outline-offset)

🧠 [Perspective](https://developer.mozilla.org/en-US/docs/Web/CSS/perspective)

🧠 [Background blend mode](https://developer.mozilla.org/en-US/docs/Web/CSS/background-blend-mode)

🧠 [Overflow](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow)

🧠 [Clip path](https://developer.mozilla.org/en-US/docs/Web/CSS/clip-path)

🧠 [Box Decoration Break](https://developer.mozilla.org/en-US/docs/Web/CSS/box-decoration-break)

🧠 [Shape outside](https://developer.mozilla.org/en-US/docs/Web/CSS/shape-outside)

🧠 [Figure HTML Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/figure)

🧠 [Filter property to create blur efect](https://developer.mozilla.org/es/docs/Web/CSS/filter)

🧠 [Object Fit](https://developer.mozilla.org/en-US/docs/Web/CSS/object-fit)

🧠 [Placeholder-shown to inputs](https://developer.mozilla.org/en-US/docs/Web/CSS/:placeholder-shown)

🧠 [Sibling selector](https://developer.mozilla.org/en-US/docs/Web/CSS/Adjacent_sibling_combinator)

🧠 [Cubic Bezier Transition](https://developer.mozilla.org/en-US/docs/Web/CSS/easing-function)

🧠 [Cubic Bezier Transition in CSS-TRICKS](https://css-tricks.com/advanced-css-animation-using-cubic-bezier/)

🧠 [Display Property](https://developer.mozilla.org/en-US/docs/Web/CSS/display)

🧠 [middle hyphen Property to text](https://developer.mozilla.org/en-US/docs/Web/CSS/hyphens)



---
### TOOLS:

🧠 [Video to Covers](https://coverr.co/)

🧠 [Icons](https://linea.io/)

🧠 [Glyphs](https://css-tricks.com/snippets/html/glyphs/)

🧠 [Free image](https://unsplash.com/)

🧠 [Generate Cubic Beziers 1](https://easings.net/)

🧠 [Generate Cubic Beziers 2](https://cubic-bezier.com)

🧠 [Generate Cubic Beziers 3](https://cubic-bezier.com)

🧠 [Simulate Devices](https://sizzy.co/)

---
### 🧠 ADVICES:

- Convert px to rem
    -   Create a base unit in pixel.
    -   use that unit to based in rem units.
- The unit Rem is not supported by Internet 9

- To define the size in the box model without padding o margin values by default
  We should define the property [`box-sizing: boder-box`](https://developer.mozilla.org/es/docs/Web/CSS/box-sizing).

- To generate multiple elements with childen you can use
  ` .composition>(img.composition__photo.composition__photo--p1)*3`
  The result is:
  ```
    <div class="composition">
      <img src="" alt="" class="composition__photo composition__photo--p1">
      <img src="" alt="" class="composition__photo composition__photo--p1">
      <img src="" alt="" class="composition__photo composition__photo--p1">
    </div>
  ```
  