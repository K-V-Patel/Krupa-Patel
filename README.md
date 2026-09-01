# Krupa Patel — personal website

Static site. No build step, no dependencies.

```
index.html   markup
styles.css   styles (light + dark theme)
script.js    theme toggle, scroll reveal, active nav
Krupa_Patel_Resume.pdf   linked by the "Download résumé" button
```

## Preview locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy (GitHub Pages — free)

1. Create a repo named `<your-github-username>.github.io`.
2. Push these files to the `main` branch.
3. Settings → Pages → Source: `main` / root.
4. Live at `https://<your-github-username>.github.io` within a minute or two.

Netlify or Cloudflare Pages work too: drag the folder onto their dashboard.

## Before publishing

- Add university name and graduation year in the Education block.
- Optionally add a headshot: drop `me.jpg` in this folder and add an `<img>` in the hero.
