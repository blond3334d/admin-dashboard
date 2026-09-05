# Admin Dashboard: Daredevil Themed
A project from The Odin Project's intermediate HTML and CSS course.
<h4><a href="https://blond3334d.github.io/admin-dashboard/">Live Preview</a></h4>

## Concepts Applied

- **CSS Grid** — the main focus of this project. I practiced grid positioning and learned several core concepts:
  - `grid-template-columns` and `grid-template-rows` for defining the page's tracks.
  - Dynamic positioning properties that make layouts responsive without media queries:
    - `auto-fill` and `auto-fit`
    - Fractional units (`fr`)
    - `repeat()`, `clamp()`, `minmax()`

- **SVG** — learned how to embed SVGs directly in HTML, and the difference between:
  - **Linked** (`<img>`) — not accessible to CSS.
  - **Inline** — lives in the DOM, so it can be styled and customized with CSS.
  - Also learned the **SVG sprite** pattern: defining a set of icons once inside `<symbol>` tags, then referencing them anywhere with `<use>`.
