# Resizing Elements + Scroll and Impact on Layout Stability

This repository attempts to demonstrate if it is safe to resize an element and restore scroll position in the same microtask and maintain layout stability.

## How to run

1. NPM Install, `npm i`
2. Run local server, `npm run start`
3. Visit `http://localhost:5000/` in a Chromium based browser capable of capturing layout stability.
4. Experiment with enabling and disabling resizing on an interval for the one resizeable area, and scrolling around the document. Monitor Layout Stability as you do.

## Feedback?

File an issue here!