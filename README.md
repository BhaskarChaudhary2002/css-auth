# Simple Login Page

A minimal static login page (front-end only) with basic validation and styling.

## Overview
This project contains a simple login form that validates empty fields and shows a status message. There is no backend — the validation runs entirely in the browser.

## Usage
- Open the page in your browser: [index (1).html](index (1).html)
- Enter a username and password and click the Login button to trigger [`login()`](index (1).html).
- Click Reset to clear the form; the reset behavior is implemented in [`resetForm()`](index (1).html).

## Files
- [index (1).html](index (1).html) — main HTML and inline script (includes [`login()`](index (1).html) and [`resetForm()`](index (1).html)).
- [index.css](index.css) — styles for the login form.
- [README.md](README.md) — this file.

## Important IDs / Selectors
- Form: `#loginForm` — defined in [index (1).html](index (1).html)
- Inputs: `#username`, `#password` — defined in [index (1).html](index (1).html)
- Message: `#message` — defined in [index (1).html](index (1).html)
- Styles: edit [index.css](index.css) to change colors, layout, or responsiveness.

## Customization
- Change primary/background colors in [index.css](index.css).
- Replace inline script in [index (1).html](index (1).html) with an external JS file if you want to add authentication or client-side enhancements.

## Notes
- This is purely client-side and not secure for real authentication.
- To extend, add a backend endpoint and submit the form via fetch/XHR instead of using the current inline validation.
