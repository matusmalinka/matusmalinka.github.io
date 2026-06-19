# malinka.online

Personal site for Matus Malinka — a Mr. Robot–themed terminal interface.
Static HTML/CSS/JS, no build step, no dependencies.

## Structure

```
index.html          # landing page  →  /
resume/index.html   # resume (man page)  →  /resume
contact/index.html  # contact + socials  →  /contact
CNAME               # custom domain: malinka.online
.nojekyll           # serve files as-is (skip Jekyll processing)
```

## Hosting

Served via GitHub Pages from the default branch root. The `CNAME` file
points the site at the apex domain `malinka.online`.
