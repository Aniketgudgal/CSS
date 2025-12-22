# Grid Template 4

![Preview — desktop](img/screenshort-1.png)

![Preview — mobile/stacked](img/screenshort-2.png)

Overview
--------

This layout demonstrates a simple one-column CSS Grid page with three main rows: `header`, `text-content` (hero/background), and `footer`. The header uses an internal grid to place the logo, navigation, and right-side action (contact button).

Files
-----

- `index.html` — Demo markup with semantic sections: header, text-content, footer.
- `index.css` — Grid definitions and responsive media queries.
- `img/` — Images used by the layout; preview images are included in this README (`img/screenshort-1.png`, `img/screenshort-2.png`).

Layout details
--------------

- Top-level grid: `grid-template-rows: 60px 100vh 60px;` places a fixed header, a full-height hero area, and a footer.
- Header: implemented as a nested grid (`grid-template-columns: 20% 65% 15%`) for logo, menu, and icons-right areas. On small screens a media query reflows the header into two rows so the menu stacks below the logo and icons.
- Text-content: uses a background image (`img/content-img.jpg`) sized to `cover` for a hero/banner effect.

Responsive behavior
-------------------

- Media queries reduce the header height and switch its internal grid to two rows on narrow viewports (`max-width: 400px`), and adjust the hero background sizing to `contain` and a smaller height.

Customization
-------------

- Change row heights: edit `grid-template-rows` in the `.container` rule.
- Swap header column ratios: adjust `grid-template-columns` in `.header` to change menu/logo sizing.
- Replace the SVG preview files with actual PNG screenshots named the same to show real captures in the README.

Viewing
-------

- Open `index.html` in a browser to view the demo locally.
