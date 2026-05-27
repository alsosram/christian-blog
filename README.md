# Faith & Fellowship

A Christian blog built with vanilla HTML, CSS, and JavaScript — statically hosted on GitHub Pages.

**Site:** https://alsosram.github.io/christian-ricanblog/

## Features

- Single-page blog with Hero, Latest Posts, Subscribe, About, and Contact sections
- Dynamic content via `site-config.json` — edit hero text, background image, about section, and footer from the admin panel
- Blog posts stored as individual JSON files under `posts/`
- Admin panel at `/admin.html` with:
  - Post CRUD (create, edit, delete)
  - Site settings editor
  - Multi-factor authentication (TOTP via Google Authenticator)
  - Recovery codes for account recovery
  - Change password
- Subscription form (Formspree-ready)
- Fully responsive design

## Tech Stack

- HTML / CSS / JavaScript (vanilla)
- GitHub Pages for hosting
- GitHub API for content management (via admin panel)
- Web Crypto API for TOTP and password hashing
- QRCode.js for MFA QR codes

## Usage

1. Clone the repo
2. Edit `site-config.json` or use the admin panel
3. Add posts by creating `posts/{slug}.json` files and registering them in `posts/posts.json`
4. Push to `main` — GitHub Pages deploys automatically
