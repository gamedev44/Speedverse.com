# SpeedVerse.com

Welcome to the official repository for **SpeedVerse.com**, the online HQ for SpeedVerse—a dynamic racing experience featuring muscle cars, exotics, off-roaders, and more.

---

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Project Structure](#project-structure)
4. [Usage](#usage)
5. [Deployment](#deployment)
6. [Contributing](#contributing)
7. [License](#license)

---

## Overview
SpeedVerse.com is a static website that showcases high-performance vehicles built for speed and durability. It includes:
- A **splash screen** (`index.html`) introducing the brand.
- A **Home page** (`Home.html`) with featured content, hero images, and call-to-action links.
- A **Garage** (`Garage.html`) displaying on-road and off-road vehicles with categories and specs.
- A **Media** page (`Media.html`) hosting images, videos, and community highlights.
- An **Updates** page (`Updates.html`) listing recent news, plus an auto-updating GitHub commits section.

---

## Features
- **Fully Hardcoded Data**: No external JSON fetch—each page has its content inline.
- **Category Navigation**: Toggle between Onroad and Offroad, plus categories like Sport, Casual, Muscle, etc.
- **Search/Highlight**: A simple search bar highlights matching text within the page.
- **Splash Screen**: A 10-second splash that fades into the Home page.
- **Responsive**: Basic responsiveness with mobile-friendly meta tags.
- **Footer Sitemap**: Expandable “Sitemap” in the footer for easy navigation to terms, privacy, etc.

---

## Project Structure

```
.
├── index.html           # Splash screen
├── Home.html            # Main homepage with hero, media, etc.
├── Garage.html          # Vehicle categories (Onroad/Offroad) & specs
├── Media.html           # Image/video gallery
├── Updates.html         # Latest updates & GitHub commits
├── Assets/
│   └── images/          # Images for homepage, cars, etc.
│   └── videos/          # Video(s) used on homepage or media page
└── README.md            # This file
```

**Note**: In this version, each HTML file contains its own `<style>` block. No separate `style.css` is needed.

---

## Usage
1. **Clone or Download** this repo.
2. **Open** any of the HTML files in your browser:
   - `index.html` for the splash screen (redirects to `Home.html` after 10s).
   - `Home.html` for the main site landing.
   - `Garage.html` to explore vehicle categories.
   - `Media.html` for images & videos.
   - `Updates.html` for recent news and GitHub commits feed.

3. **GitHub Commits Section** (on `Updates.html`):
   - The site fetches commits from [gamedev44/SpeedVerseInvision](https://github.com/gamedev44/SpeedVerseInvision) every 5 seconds.
   - If your repo is private, you’ll need to adjust or remove this feature.

4. **Search**: Type a keyword in the search bar and press **Enter**. Matching text is highlighted.

---

## Deployment
- **GitHub Pages**: Just commit/push these HTML files to your repo’s `main` (or `gh-pages`) branch, then enable GitHub Pages in your repo settings.
- **Any static host** (e.g. Netlify, Vercel, etc.): Drag-and-drop the entire folder or push via Git. The site is purely static—no backend needed.

---

## Contributing
- Fork the repo and create a new branch for your feature or fix.
- Commit changes with clear messages.
- Open a Pull Request describing your changes.

We appreciate any help improving the site’s design, content, or new vehicle categories!

---

## License
This project is provided under the [MIT License](LICENSE) (or your chosen license). Feel free to use, modify, and distribute for your own projects, but please link back to the original SpeedVerse if you do.

---

**Enjoy the SpeedVerse!** If you have questions or feedback, open an issue or reach out via [Discord](https://discord.gg/speedverse).
```