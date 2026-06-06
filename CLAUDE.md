# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static HTML5 personal portfolio site for Will McDowell, an IT support technician. There is no build system, package manager, framework, or test suite — it is pure vanilla HTML, CSS, and JavaScript.

## Running the Site

Open `index.html` directly in a browser. No build step or server is required.

## Project Structure

- `index.html` — single-page site; all content lives here
- `styles/style.css` — stylesheet; currently contains debug outlines on all major elements (red on `body`, green on `header`/`main`, blue on child elements) to visualize the box model during development
- `scripts/app.js` — empty placeholder for future JavaScript
- `images/` — static assets (`skibbidy.jpeg` profile photo, `in-progress.gif` construction indicator)

## Current State & Conventions

- The site is intentionally under construction. The debug CSS borders in `style.css` are deliberate, not accidental — they expose the box model while layout is being developed.
- Several CSS rules are commented out in `style.css`; these are in-progress positioning experiments, not dead code to be removed.
- The LinkedIn URL in `index.html` (`www.linkedin.com/wilmcdowell`) may be incomplete — verify before updating.
- `app.js` is empty and intended for future interactivity; do not remove it.
