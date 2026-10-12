# CSS - Laundry Services Hamburger Menu in Mobile

A responsive laundry services landing page built with plain HTML and CSS (no Bootstrap, no JavaScript).

## Features
- **Navbar**: uses `display: flex` (no inline), nav link text, logo and username shrink on tablet, and links are hidden on mobile (only Logo + Username remain).
- **Hamburger Menu (mobile)**: a hamburger icon button is added to the navbar. It is hidden by default and only visible on mobile view. The menu list is a `div` positioned `absolute` on the right side of the screen with `display: none` by default.
- **Showing the list on click (no JS)**: the hamburger icon is wrapped in a `<button>`, and the `:focus` pseudo-class is used to display the list — `.hamburger:focus ~ .menu-list { display: block; }`. This works because the menu list is a sibling of the button.
- **Hero Section**: text and image sizes reduce on tablet, and on mobile the layout switches to `flex-direction: column` with the image stacked below the text.

## Files
- `index.html` – page markup
- `style.css` – styles + media queries (tablet `max-width: 1024px`, mobile `max-width: 600px`)

## Run
Open `index.html` in a browser, or use the Live Server extension in VS Code. Switch to mobile view (≤600px) and click the hamburger icon to open the menu.
