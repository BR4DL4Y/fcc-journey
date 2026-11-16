# Accessibility Quiz Webpage 

## Key Concepts Learned

* **Web Accessibility (a11y):**
  * Using the `.sr-only` utility class to visually hide helper text while keeping it readable for screen readers.
  * Wrapping smooth scrolling inside `@media (prefers-reduced-motion: no-preference)` to respect users with vestibular disorders or motion sensitivity.
  * Structuring forms semantically with `<fieldset>`, `<legend>`, `<label>`, and ARIA attributes (`role="region"`, `aria-labelledby`).
* **Modern & Responsive CSS:**
  * Dynamic sizing with mathematical functions like `min()`, `max()`, and `aspect-ratio` to adapt logos and typography without complex media queries.
  * Logical properties (`padding-inline-start`, `margin-block`) and direct child selectors (`>`) for clean navigation styling.
  * Using pseudo-elements (`::before`) to inject visual prefixes without cluttering screen reader output.

## Customizations & Improvements

Beyond the base freeCodeCamp steps, I started tweaking the UI in CodeSandbox to improve spacing and usability:
* Added custom `margin: 6px;` and `padding: 6px;` to `select` and `textarea` elements so the form fields have better breathing room.
