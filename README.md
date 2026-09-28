# HopeClinic-Website

Landing page for **HOPE**, the free, medical student-run clinic from the AUB Faculty of Medicine in Lebanon ([@hope.aubfm](https://www.instagram.com/hope.aubfm/)).

It is a plain static site (HTML, CSS and a little JavaScript) with no build step.

```
index.html            page content
styles.css            styles; brand colours are in :root
script.js             mobile menu, sticky-nav shadow, scroll reveal
assets/logo-mark.svg  heart mark (the "O" in HOPE), also used as the favicon
```

## Preview locally

Open `index.html` in a browser, or run:

```sh
python3 -m http.server 8000
```

## Before launch

Search `index.html` for `TODO` and fill in:

- the clinic's exact address
- regular clinic days and hours
- an email or phone number, if the team wants to publish one

The heart mark is recreated from the logo. For a pixel-perfect match, replace `assets/logo-mark.svg` with the original vector file.

## Deploy

The site works on any static host. For GitHub Pages: **Settings → Pages → Deploy from branch**, then choose the branch and the `/` (root) folder.
