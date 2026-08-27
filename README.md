# aarishnaiyer.com

My personal portfolio site. A single-page overview of my experience, projects, and skills.

**[Live site](https://aarishnaiyer.com)**

I'm a second-year Computing Science student at the University of Alberta and an Ethereum Foundation Protocol Fellow, working on trust-minimized checkpoint sync for Ethereum's consensus layer in Rust. The site collects my work across the stack, from consensus-layer protocol code and low-level C systems to live web tooling.

## Tech

- Vanilla HTML, CSS, and JavaScript. Single page, no framework, no build step
- Fonts: Space Mono and Syne (Google Fonts)
- Scroll-triggered reveals via the IntersectionObserver API
- Deployed as a static site

## Running locally

The site is a static file, so any static server works:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Structure

```
index.html   # the whole site: markup, styles, and script
images/      # profile photo and assets
```

## Contact

- Site: [aarishnaiyer.com](https://aarishnaiyer.com)
- GitHub: [@aarishnaiyer](https://github.com/aarishnaiyer)
- LinkedIn: [in/aarishnaiyer](https://linkedin.com/in/aarishnaiyer)
