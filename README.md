# Chinatsu

Chinatsu is a browser-based creator vault for organizing prompts, links, images, videos, PDFs, audio, and other saved resources into collections.

## Run locally

1. Download or clone this project.
2. Open `index.html` in a modern browser.

For the most reliable experience, serve the folder using a local static web server or host it over HTTPS. The app loads Alpine.js, Tailwind CSS, Font Awesome, and export libraries from CDNs, so an internet connection is required for those resources.

## Features

- First-run welcome screen with an optional guided tour.
- Profile setup and profile editing.
- Create collections and save different types of posts and media.
- Search and organize saved content, with a bin for deleted items.
- Light and dark themes, plus optional sound and haptic feedback.
- Export vault data in supported formats from Settings.
- Responsive layouts for desktop and mobile screens.

## Data and privacy

Chinatsu is a client-side app and does not require an account or application server. Profile information, settings, and vault data are stored in the current browser's local storage; uploaded media is stored in browser IndexedDB. Data is local to that browser and device, so clearing browser storage can remove it. Use the export options in Settings to keep a backup.

## Project files

- `index.html` — the complete Chinatsu application.
- `sami-devs-splash.html` — a standalone, reusable animated splash screen.

## Hosting

The app can be deployed as a static site using a static hosting provider. Upload the project files and serve `index.html` over HTTPS. Test the app after deployment, especially media uploads and exports, and keep a separate backup of important vault data.
