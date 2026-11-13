# Abhishek Maurya — Agentic Build Portfolio

A single-file portfolio website that **builds itself in front of the visitor**. As you scroll, a team of named agent cursors flies to each block, draws a selection box, and fills the section with content.

**Live site:** https://your-site.vercel.app  <!-- replace with your Vercel URL -->

## Highlights

- **Agentic build effect:** named cursors (Arjun, Priya, Meera, Vikram and more) select, size and fill each block as it enters the screen.
- **Scroll animations:** progress bar, hero parallax, headings and ticker that react to scroll speed, count-up stats, and a drifting outlined name.
- **Bold design:** black and crimson palette, giant condensed italic type (Anton), a perspective grid floor and a rotating cursor swirl in the contact section.
- **Real content:** experience, skills, projects, certificates and achievements, all rendered from data objects at the top of the script.
- **Zero build step:** one `index.html`, plain HTML, CSS and JavaScript. No framework and no dependencies except Google Fonts.
- **Accessible and responsive:** works from phone to desktop and respects `prefers-reduced-motion`.

## Sections

Hero, tech ticker, background and philosophy, experience, projects, toolkit, certificates and achievements, and contact.

## Run locally

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
# open index.html in a browser, or serve it:
npx serve .
```

## Deploy

The site is static, so it deploys anywhere. On Vercel:

1. Push this repo to GitHub.
2. Import it at [vercel.com/new](https://vercel.com/new).
3. Leave the framework preset as **Other** and deploy.

## Customize

Open `index.html` and edit the data constants at the start of the `<script>` block:

| Constant | What it controls |
| --- | --- |
| `ROLES` | Rotating role line in the hero |
| `EXPERIENCE` | Experience rows |
| `PROJECTS` | Project rows |
| `SKILLS` | Toolkit cards |
| `CERTS` / `CERT_IMGS` | Certificate cards and images |
| `ACHIEVEMENTS` | Achievement list |
| `SOCIALS` | Social links in the contact section |

Colors and fonts are CSS variables in `:root`. The agent names and colors are in the `AG` array.

## Tech

HTML5, CSS3 (custom properties, grid, mask, perspective transforms), vanilla JavaScript (IntersectionObserver, requestAnimationFrame), Google Fonts (Anton, Manrope, JetBrains Mono).

## Contact

- LinkedIn: [abhishek-maurya](https://www.linkedin.com/in/abhishek-maurya-119907195/)
- GitHub: [AbhishekMauryaIICS](https://github.com/AbhishekMauryaIICS)
- Email: abhishekmaurya2113@gmail.com

## License

© Abhishek Maurya. All rights reserved. The code is free to study; please don't copy the content or photos.
