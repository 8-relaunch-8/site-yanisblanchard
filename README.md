# yanisblanchard.com

My personal landing page: a name, one line about what I do, a contact, a link to GitHub. Nothing more, on purpose.

- Plain HTML and CSS: no framework, no build step, no JavaScript.
- No tracker, no cookie, no third-party request. The handwritten font is self-hosted and subset to the letters of the name (3.5 kB); the rest uses the system font.
- Strict security headers (CSP, HSTS…) set in `public/_headers`, and a `security.txt` (RFC 9116).
- Hosted on [Cloudflare Pages](https://pages.cloudflare.com/): no build command, output directory `public/`.

## Layout

```
public/            the website, the only folder published
public/_headers    HTTP headers, read by Cloudflare Pages and not served
```

## Font

[Nothing You Could Do](https://fonts.google.com/specimen/Nothing+You+Could+Do) by Kimberly Geswein, under the SIL Open Font License 1.1 (`public/fonts/OFL.txt`).
