# malinka.online

Personal site for Matus Malinka — a Mr. Robot–themed terminal interface.
Static HTML/CSS/JS, no build step, no dependencies.

**Live:** [https://malinka.online](https://malinka.online)  
**Source host:** GitHub Pages (`matusmalinka.github.io`)

## Structure

```
index.html                 # landing page          →  /
resume/index.html          # resume (man page)     →  /resume
contact/index.html         # contact + socials     →  /contact
CNAME                      # custom domain: malinka.online
.nojekyll                  # serve files as-is (skip Jekyll)
favicon.ico / favicon-*.png
apple-touch-icon.png
android-chrome-*.png
site.webmanifest
```

## Features

- CRT terminal UI with typewriter intro animations
- Shared top nav across home, resume, and contact
- Responsive layout for mobile
- Favicons + web manifest
- Custom domain with HTTPS via GitHub Pages

## Hosting

Served via GitHub Pages from the default branch root.
DNS (DigitalOcean) points `malinka.online` and `www` at GitHub Pages;
the `CNAME` file pins the apex domain for Pages.
