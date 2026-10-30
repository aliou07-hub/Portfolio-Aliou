# Aliou Garga Aboubikr | Portfolio

Portfolio of Aliou Garga Aboubikr, Accounting and Finance professional (open to remote roles, US and Europe), and founder of [CvatsPro.com](https://www.cvatspro.com/).

## What is inside

Static site, no build step. `index.html` holds all the code and images. `Aboubikr_Aliou_Resume_CV.pdf` is the file behind the Download CV buttons.

- Animated 3D ID badge intro (Three.js), plays once per browser session, with a Skip button and a 2D fallback for old phones, low-end devices and reduced motion
- Language choice at the start: French or English (saved in the visitor's browser)
- Who are you? screen: client path or recruiter path (choice saved), with a Switch profile link in the header
- Client path: services, websites built, case study, WhatsApp and email buttons
- Recruiter path: skills, experience timeline, availability, Download CV and email buttons
- Small dancing robot on every page: tap it to chat. It suggests questions about Aliou and answers them (French and English)
- Times New Roman typography, 3D floating shapes and scroll-driven motion
- Full portfolio: opens from the See everything else button at the bottom of each path

Libraries (Three.js, GSAP, Lenis) load from a CDN only when needed. The site still works without them.

## Run locally

```bash
python -m http.server 8080
```
Then open http://localhost:8080

## Deploy

- GitHub Pages: push the repo, then Settings, Pages, Deploy from branch, `main` / root.
- Vercel or Netlify: import the repo, no build command, output is the root folder.

## Contact

- Email: aliougargaaboubikr@gmail.com
- Phone and WhatsApp: +237 698 828 298
- Location: Douala, Cameroon
