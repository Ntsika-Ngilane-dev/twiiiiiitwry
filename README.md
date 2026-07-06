# Tweets Mock Social Experience

A polished, self-contained mock social media web app built with plain HTML, CSS, and JavaScript. The project recreates the feel of a modern social platform with a sign-in flow, home feed, explore page, bookmarks, messages, profile pages, comments, reposts, trending topics, and theme switching.

## Overview

This project was designed as a lightweight, dependency-free social UI prototype. Instead of using a framework, it focuses on delivering a rich, interactive experience entirely in a single static page using browser-side JavaScript and local storage.

It is ideal for:
- UI prototyping
- front-end demonstrations
- mock social app concepts
- portfolio projects
- interactive static web experiments

## Key Features

### Authentication and onboarding
- Sign-in modal with name, email, and optional bio
- Optional profile picture upload during sign-in
- Persistent session state using local storage

### Home feed
- Interactive post composer
- AI-powered post suggestions
- Like, bookmark, comment, and repost actions
- Dynamic feed updates in real time

### Mock social experience
- Explore page with many mock accounts
- Dedicated profile pages for each mock profile
- Follow/unfollow actions
- Bookmarks page for saved posts
- Message view for simulated conversations

### News and trends
- Trending topic cards with live-style topic headlines
- Trend click behavior that creates a new post about that topic
- Topic-driven content generation for a more realistic feed

### Visual experience
- Light and dark mode toggle
- Polished card-based UI
- Responsive layout for desktop and smaller screens
- Custom generated avatars and profile images for mock users

## Tech Stack

- HTML5 for structure
- CSS3 for styling and layout
- Vanilla JavaScript for interactivity
- Browser localStorage for persistence

## Project Structure

The app is intentionally simple and self-contained:

- [index.html](index.html) — complete app markup, styles, behavior, and state management

## Getting Started

### Run locally
Since this project is a static web app, you do not need a build step or package manager.

1. Open the project folder in your browser.
2. Double-click [index.html](index.html), or serve it with a local static server.
3. Start interacting with the app immediately.

### Optional local server
If you prefer using a local server, you can run one from the project folder:

- Python:
  - `python -m http.server 8000`
- Node.js (if available):
  - `npx serve .`

Then open the displayed local address in your browser.

## How It Works

The application stores its state in the browser using localStorage, which means:
- your sign-in session persists across refreshes
- bookmarks and posts remain available locally
- profile state and feed interactions survive reloads

All UI rendering is handled dynamically through JavaScript, making the experience feel interactive while remaining lightweight.

## Customization

You can easily customize the app by editing [index.html](index.html):
- change colors and typography in the CSS section
- update the sample profiles and posts in the data generation logic
- modify the trends and live-style headlines
- extend interactions such as comments, reposts, and bookmarks

## Notes

This app is intentionally a mock experience and not a production-ready social platform. It is designed for demonstration, prototyping, and educational purposes.

## Future Improvements

Potential enhancements include:
- real backend integration
- authentication with a real service
- persistent cloud storage
- richer animations and transitions
- responsive mobile-first refinements
- real news API integration

## License

This project is provided as a simple demo and is free to use and modify for personal or educational purposes.
