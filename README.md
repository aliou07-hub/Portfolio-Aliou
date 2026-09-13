# Aliou Garga Aboubikr — Portfolio

Personal portfolio of Aliou Garga Aboubikr — Entrepreneur, Web Developer & Digital Consultant, and founder of [CvatsPro.com](https://www.cvatspro.com/).

## About this site

Single-file, static HTML/CSS/JS website (no build step, no dependencies). Everything — images, certificates, logos — is embedded directly in `index.html` as base64 data, so the site works by simply opening the file, and deploys as-is to any static host.

**Features:**
- Bilingual — English / Français (language switch in the top navigation, saved in the visitor's browser)
- Sections: Home, About, Services, Web Projects, Entrepreneurship, CvatsPro.com, Professional Experience, Certifications, Gallery, Contact
- Fully responsive (mobile / tablet / desktop) with a mobile menu
- 3D-styled interactions: mouse-reactive hero photo, tilt-on-hover cards, animated multi-color bubbles, flip animations on certificate cards

## Running locally

No build tools needed. Either:
- Open `index.html` directly in a browser, or
- Serve it locally:
  ```bash
  python -m http.server 8080
  ```
  then visit `http://localhost:8080`

## Deploying

This is a single static file, so it deploys to any static host with zero configuration:

- **GitHub Pages:** push this repo, then enable Pages (Settings → Pages → Deploy from branch → `main` / root). The site will be live at `https://<username>.github.io/<repo-name>/`.
- **Vercel / Netlify:** import the repo and deploy with no build command — output is `index.html` at the root.

## Contact

- Email: aliougargaaboubikr@gmail.com
- Phone: +237 698 828 298
- Location: Douala, Cameroon
- Product: [CvatsPro.com](https://www.cvatspro.com/)
