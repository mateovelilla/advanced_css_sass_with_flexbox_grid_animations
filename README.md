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

🧠 [Glyphs](https://css-tricks.com/snippets/html/glyphs/)

🧠 [Outline: border in box](https://developer.mozilla.org/en-US/docs/Web/CSS/outline)

🧠 [Outline-offset: sets the amount of space between an outline and the edge or border of an element.](https://developer.mozilla.org/en-US/docs/Web/CSS/outline-offset)

🧠 [Icons](https://linea.io/)

🧠  [Perspective](https://developer.mozilla.org/en-US/docs/Web/CSS/perspective)

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
  