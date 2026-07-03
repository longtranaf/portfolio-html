# Tran Long — Portfolio (HTML / CSS / JS)

A static, framework-free version of the portfolio. No build step, no
dependencies — just plain HTML, CSS, and JavaScript.

## Structure

```
portfolio-html/
├── index.html        # All content and page structure
├── css/
│   └── styles.css     # Design tokens + all section styles
├── js/
│   └── main.js        # Scroll reveal, sticky header, mobile menu, footer year
└── favicon.svg
```

## Running locally

Because it's static, just open `index.html` in a browser. For a local server
(so relative paths and fonts behave exactly like production):

```bash
# Python
python -m http.server 8000

# or Node
npx serve .
```

Then visit http://localhost:8000.

## Editing content

All content lives directly in `index.html` — edit the profile intro, projects,
skills, and experience there. Section styles are grouped and labelled in
`css/styles.css`.

## Deploying

Any static host works (GitHub Pages, Netlify, Vercel, Cloudflare Pages). For
GitHub Pages, push the folder contents and point Pages at the branch/root.
