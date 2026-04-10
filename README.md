# Canadian Network for Complex Systems — Website

Static marketing site for [cncs-canada.org](https://cncs-canada.org/).

## Stack
- Vanilla HTML, CSS, JavaScript — no build step
- Hosted on Netlify, deployed from this GitHub repo on push to `main`
- Domain managed via Hover DNS

## Local development
Open `index.html` in a browser, or serve locally:

```bash
python -m http.server 8000
# or
npx serve .
```

## Structure
```
.
├── index.html
├── about.html
├── get-involved.html
├── contact.html
├── css/styles.css
├── js/main.js
├── images/logo.jpg
└── netlify.toml
```

## Deployment
Pushes to `main` automatically deploy via Netlify. No manual build step required.
