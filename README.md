# Google Search Front-End

A front-end for Google Search built for CS50 Web Programming with Python and JavaScript (Project 0).

Three static HTML pages that submit real GET requests to Google using the same parameters Google's own forms use.

Live: https://ismail-mah.github.io/search/

## Pages

- **index.html** — main search with Google Search and I'm Feeling Lucky buttons
- **images.html** — image search (uses hidden `tbm=isch` parameter)
- **advanced.html** — advanced search with four filter fields (`as_q`, `as_epq`, `as_oq`, `as_eq`)

## Usage

Just open `index.html` in a browser. No server or build step needed.

## Structure

```
project0/
├── index.html
├── images.html
├── advanced.html
├── images/
└── styles/
    ├── common.css        # shared header, footer, reset
    ├── index.css
    ├── image-search.css
    └── advanced-search.css
```

## Author

Ismail M. Adam — 2026