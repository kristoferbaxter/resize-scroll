# Resizing Elements + Scroll and Impact on CLS

This repository attempts to demonstrate if it is safe to resize an element and restore scroll position in the same microtask and prevent a CLS score change.

## How to run

1. NPM Install, `npm i`
2. Run local server, `npm run start`
3. Visit `http://localhost:5000/` in a Chromium based browser capable of capturing CLS.
4. Experiment with enabling and disabling resizing on an interval for the one resizeable area, and scrolling around the document. Monitor CLS as you do.

## Feedback?

File an issue here!