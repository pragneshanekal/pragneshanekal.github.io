# Pragnesh Anekal — Personal Portfolio

Personal portfolio site for [Pragnesh Anekal](https://pragneshanekal.github.io), a Data Engineer based in Boston, MA.

## Live Site

**[pragneshanekal.github.io](https://pragneshanekal.github.io)**

## What's on the site

- **About** — who I am and what drives me
- **Experience** — work history at Staples, Northeastern University, ReVx Energy, and Datasol Innovative Labs
- **Projects** — things I've built, updated as I ship more
- **Skills** — animated skill bars across Data Engineering and AI Engineering, plus supporting tools
- **Education** — MS at Northeastern, BE at BMS College of Engineering
- **Passions** — what I'm into beyond the day job
- **Writing** — articles I've written, with more to come

## Tech

Pure static site — single `index.html` with embedded CSS and vanilla JavaScript. No build step, no framework, no dependencies beyond Google Fonts.

Interactive features:
- Typing animation in the hero
- Scroll-triggered reveal animations via IntersectionObserver
- Animated skill progress bars
- Active nav highlighting on scroll

## Deployment

Deployed automatically to GitHub Pages on every push to `main` via the GitHub Actions workflow in `.github/workflows/static.yml`.

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```
