# Layout 2 — Layout & Login

This folder contains the HTML pages for Layout 2:

- layout.html — the main page layout (header, content areas, footer).
- loginForm.html — standalone login form (markup + basic validation/styles).

Screenshots
- Layout (homepage / main layout):
  ![Layout preview](img/layout2-main.png)

- Login form:
  ![Login form preview](img/layout2-login.png)

Notes
- Ensure any referenced CSS, JS, and image assets are placed relative to the Layout2 folder as used in the HTML files.

Topics
- Responsive page structure (header, content regions, footer).
- Login form UX: fields, labels, submit flow, and error states.
- Navigation patterns and visual hierarchy.
- Form validation (client-side feedback) and basic accessibility.
- Component layout: cards, grids, and utility spacing.

Concepts demonstrated
- Semantic HTML and logical document structure (header, main, footer, form).
- Responsive layout using CSS Grid/Flexbox for adaptable content regions.
- Progressive enhancement: usable without JavaScript; enhanced with JS for validation/interaction.
- Accessible form patterns: proper labels, focus states, and ARIA where needed.
- Clear validation feedback and form state management (success, error, loading).
- Reusable component approach (modular CSS classes for header, card, form).
- Simple secure-login UX considerations (avoid leaking error details, use HTTPS in production).