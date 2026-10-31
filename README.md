# Saba Mahek & Mohammed Zaid — Wedding Invitation

A responsive, single-page wedding invitation website built with HTML, CSS, and vanilla JavaScript.

## Run locally
Open `index.html` in a modern browser. An internet connection is needed for the Google Fonts; the site and artwork are otherwise bundled locally.

## Deploy
Upload the contents of this folder to GitHub Pages, Netlify, or any static web host. Keep the `assets` directory next to `index.html`.

## Included
- Animated invitation cover and golden-particle canvas
- Responsive navigation and smooth section scrolling
- Wedding countdown to 29 November 2026 (India time)
- Invitation text, Nikah and dinner details, venue directions
- Locally bundled AI-generated fairytale wedding artwork
- Optional gentle synthesized ambient tones (only starts after a visitor clicks Music)
- RSVP form that prepares an email using the visitor's email app

## Notes
- Google Maps links open a location search for the venue names provided. Please verify the venue pins and replace the search URL with a confirmed pin URL if you have one.
- The RSVP form uses `mailto:` because static hosting does not include a server to collect submissions. For online collection, connect a form endpoint (for example, Netlify Forms) before publishing.
- Fonts are loaded from Google Fonts with system fallbacks.
