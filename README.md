# Samuel Adiprabowo — Personal Website

A static personal website for **Samuel Adiprabowo**, Marine & Ocean Engineer,
inspired by the academic *Minimal Mistakes* aesthetic (as seen on similar
personal academic sites).

## Pages

| Page          | File                |
| ------------- | ------------------- |
| Home / About  | `index.html`        |
| Résumé & CV   | `resume.html`       |
| Publications  | `publications.html` |
| Blog          | `blog.html`         |
| News          | `news.html`         |
| Contact       | `contact.html`      |

## Structure

```
web_adiprabowo_pw/
├── index.html
├── resume.html
├── publications.html
├── blog.html
├── news.html
├── contact.html
├── blog/
│   └── rayleigh-fractionation.html   (sample post)
└── assets/
    ├── css/main.css
    ├── js/main.js
    └── images/                       (add profile.jpg here)
```

## Run locally

There is no build step — just open `index.html` in a browser, or serve the
folder with any static server. For example:

```bash
# Python
python -m http.server 8000
# then visit http://localhost:8000
```

or

```bash
# Node (npx)
npx serve .
```

## Deploy

The site is plain HTML/CSS/JS, so it can be deployed anywhere that hosts static
files: GitHub Pages, Netlify, Vercel, Cloudflare Pages, or a simple web server.

## Customizing

- **Your contact details** — edit `contact.html` and the nav/footer links in
  each page (email, phone, LinkedIn, Google Scholar, GitHub URLs).
- **Your portrait** — drop an image at `assets/images/profile.jpg` and uncomment
  the `<img>` placeholder in `index.html`.
- **Publications** — replace the placeholder entries in `publications.html` with
  the exact titles, journals, DOIs, and PDF links from your publication records.
- **Theme colors** — edit the CSS custom properties at the top of
  `assets/css/main.css` (`--accent`, `--heading`, `--link`, etc.).
- **Blog posts** — create new HTML files under `blog/` and link them from
  `blog.html`.
```