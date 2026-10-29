# yanisblanchard.com

My personal landing page: a name, a contact, a link to GitHub. Nothing more, on purpose.

- Plain HTML and CSS: no framework, no build step, no JavaScript.
- No tracker, no cookie, no third-party request. The font is self-hosted and subset to the few letters the page uses (3.5 kB).
- Strict security headers (CSP, HSTS…) set in `sws.toml`, and a `security.txt` (RFC 9116).
- Served by [Static Web Server](https://static-web-server.net/) (`sws.toml`). Only `public/` is served. Hosting: to be decided.

## Layout

```
public/      the website, the only folder served
sws.toml     Static Web Server configuration (headers, cache)
```

## Font

[Nothing You Could Do](https://fonts.google.com/specimen/Nothing+You+Could+Do) by Kimberly Geswein, under the SIL Open Font License 1.1 (`public/fonts/OFL.txt`).
