# tools

One-off static pages, served at **https://tools.etsica.com** by GitHub Pages.

- `name.html` at the root is served at `/name` (Pages drops the `.html`).
- Bigger pages get a folder: `name/index.html` is served at `/name/`, with its images and scripts beside it.
- Add a line to `index.html` for each new page, newest first.
- Pages load nothing from outside Etsica: only this repo or `etsica.com` and its subdomains. Shared fonts live in `fonts/`, declared in `css/fonts.css`.
- Push to `main` and it is live in about a minute.

`CNAME` holds the custom domain; don't delete it. `.nojekyll` makes Pages serve files as they are. `robots.txt` keeps everything out of search engines; pages are shared by link.

Everything here is public, including the git history. No real names, photos or anything from Etsica customers.
