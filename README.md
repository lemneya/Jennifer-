# Lawyer Productivity App (Agent MVP)

A lightweight, static HTML app that suggests tasks, document tags, and time entries based on simple inputs. Built with Tailwind (CDN) for quick iteration.

## Run
- Open `index.html` directly in your browser.
- For development styles with Tailwind JIT:
  ```bash
  npm install
  npm run watch:css
  # open index.html (the CSS will update as you edit classes)
  ```

## Build CSS
- Generate a minimized CSS bundle:
  ```bash
  npm run build:css
  ```
  This writes `public/styles.css` which `index.html` loads.

## Accessibility
- Includes an accessible modal dialog (keyboard + Escape, focus handling)
- Live announcements for dynamic suggestions (`aria-live="polite"`)

## Production tips
- Keep using the built CSS (no CDN) for faster loads and deterministic styling.
- Consider pinning font files locally for improved privacy and reliability.
- Serve with proper cache headers.

## License
MIT