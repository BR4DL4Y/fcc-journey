# Accessibility Quiz Webpage 

## Key Concepts Learned

* **Web Accessibility (a11y):**
  * Using the `.sr-only` utility class to visually hide helper text while keeping it readable for screen readers.
  * Wrapping smooth scrolling and animations inside `@media (prefers-reduced-motion: no-preference)` to respect users with vestibular disorders or motion sensitivity.
  * Structuring forms semantically with `<fieldset>`, `<legend>`, `<label>`, and ARIA attributes (`role="region"`, `aria-labelledby`).
* **Modern & Responsive CSS:**
  * Dynamic sizing with mathematical functions like `min()`, `max()`, and `aspect-ratio` to adapt logos and typography without complex media queries.
  * Logical properties (`padding-inline-start`, `margin-block`) and direct child selectors (`>`) for clean navigation styling.
  * Using pseudo-elements (`::before`) to inject visual prefixes without cluttering screen reader output.

## Customizations & Improvements

Rather than leaving the boilerplate code strictly as provided in the curriculum, I experimented with subtle UI tweaks in CodeSandbox—keeping changes modest so as not to break the core accessibility structure:

* **Form Spacing & Focus States:** Added `margin` and `padding` to `select` and `textarea` elements for better breathing room, along with custom `:focus` borders for clearer visual feedback.
* **Interactive Polish:** Added rounded corners, color transitions, and `:hover` states to the submit button, plus a subtle upward lift (`translateY`) on navigation items (safely scoped inside `prefers-reduced-motion`).
* **Navigation & Readability:** Wrapped the header logo in an external link (`<a>` with `display: flex` alignment) and refactored the HTML indentation with section comments for cleaner code readability.
