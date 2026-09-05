# Portfolio

Personal site for Enoch Adelowo, backend focused software engineer working in Java and Spring Boot.

**Live at [portfolio-moxy2.vercel.app](https://portfolio-moxy2.vercel.app)**

## About this build

A single static HTML file with no framework, no build step and no dependencies. The
whole site is one document with the styles inline, which keeps it fast to load and
trivial to deploy. The only JavaScript on the page is a short script that hides the
architecture figures if their image files are unavailable, so the layout never breaks.

Type is set in Newsreader for prose and IBM Plex Mono for technical detail, served from
Google Fonts. The palette runs on a deep petrol ground with a brass accent.

Built to be responsive down to mobile, keyboard navigable with visible focus states, and
respectful of reduced motion preferences.

## Structure

```
├── index.html    the entire site
├── cv.pdf        linked from the CV buttons
└── images/       architecture diagrams
```

## Running locally

Clone the repo and open `index.html` in a browser. There is nothing to install.

For a local server, so relative paths behave exactly as they do in production:

```bash
python3 -m http.server 8000
```

Then visit `localhost:8000`.

## Deployment

Hosted on Vercel as a static site with no build command or output directory configured.
Pushes to `main` deploy automatically.

## Contact

[enoch0272@gmail.com](mailto:enoch0272@gmail.com) · [LinkedIn](https://www.linkedin.com/in/enoch-swe/)
