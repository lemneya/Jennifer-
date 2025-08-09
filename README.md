# Lawyer Productivity App (Agent MVP)

A lightweight, static HTML app that suggests tasks, document tags, and time entries based on simple inputs. Built with Tailwind (CDN) for quick iteration.

## Run
- Open `index.html` directly in your browser.

## Accessibility
- Includes an accessible modal dialog (keyboard + Escape, focus handling)
- Live announcements for dynamic suggestions (`aria-live="polite"`)

## Production tips
- Replace Tailwind CDN with a built CSS bundle so only used utilities ship:
  - Using Tailwind CLI:
    ```bash
    npm create tailwind@latest
    # adapt to generate a minimal CSS that includes used utilities
    ```
- Keep the Google Fonts preconnects. Consider self-hosting fonts for better privacy and performance.
- Serve with proper cache headers.

## License
MIT