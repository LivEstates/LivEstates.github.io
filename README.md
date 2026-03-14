# LivEstates Website

Static marketing landing page for [LivEstates](https://livestates.tech), a social media platform dedicated to revolutionizing property presenting in the real estate industry. The site is hosted on GitHub Pages with a custom domain.

## Live Site

**URL:** [https://livestates.tech](https://livestates.tech)

## Tech Stack

- HTML5
- CSS3
- [Bootstrap 3](https://getbootstrap.com/) (navbar, grid system, glyphicons)
- [jQuery](https://jquery.com/) (smooth scrolling, UI interactions)
- [Swipebox](https://brutaldesign.github.io/swipebox/) (lightbox gallery)

No build process is required — the site is pure static HTML/CSS/JS.

## Pages

| File | Description |
|------|-------------|
| `index.html` | Home page — hero banner, about section, services overview, solutions gallery |
| `services.html` | Services offered by LivEstates |
| `contact.html` | Contact information |
| `about.html` | About the company |
| `gallery.html` | Image gallery |

### Policy Pages (`/policy`)

| File | Description |
|------|-------------|
| `privacy-policy.html` | Privacy policy |
| `terms-and-conditions.html` | Terms and conditions |
| `live-user-rules-streamers.html` | Rules for streamers |
| `live-user-rules-viewers.html` | Rules for viewers |

## Project Structure

```
.
├── css/            # Stylesheets (Bootstrap, custom styles, gallery)
├── fonts/          # Web fonts
├── images/         # Site images and assets
├── js/             # JavaScript (jQuery, Bootstrap, plugins)
├── policy/         # Legal and policy pages
├── CNAME           # Custom domain configuration (livestates.tech)
├── index.html      # Home page
├── about.html
├── contact.html
├── gallery.html
└── services.html
```

## Local Development

No build tools or dependencies to install. To run the site locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/LivEstates/LivEstates.github.io.git
   cd LivEstates.github.io
   ```
2. Open `index.html` in a browser, or start a local server:
   ```bash
   python3 -m http.server 8000
   ```
3. Visit `http://localhost:8000` in your browser.

## Deployment

The site is deployed automatically via [GitHub Pages](https://pages.github.com/). Any push to the `main` branch is published to [https://livestates.tech](https://livestates.tech).

The custom domain is configured through the `CNAME` file in the repository root.

## License

Copyright Virtual Hybrid Inc. All rights reserved.
