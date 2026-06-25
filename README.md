# Portfolio — Ximena Quevedo

Personal portfolio website. Static site (HTML + CSS), hosted free on GitHub Pages.

## Local preview

Open `index.html` directly in a browser, or serve it:

```bash
cd portfolio
python3 -m http.server 8000
# visit http://localhost:8000
```

## Deploy to GitHub Pages (free)

1. Create a **public** repo on GitHub named `<your-username>.github.io`
   (a "user site" — gives the clean URL `https://<your-username>.github.io`).
2. Push this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
   git push -u origin main
   ```
3. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch → `main` / root**.
4. Wait ~1 minute. Site is live at `https://<your-username>.github.io`.

## Custom domain (optional, ~10 €/year)

Buy a domain (Namecheap, Porkbun, IONOS …), then in **Settings → Pages → Custom domain**
enter it and add the DNS records GitHub shows. Hosting stays free; you only pay the domain.

## Before going live — checklist

- [ ] Replace the IEEE email placeholder in `index.html` (`your.alias@ieee.org`)
      with your activated IEEE alias.
- [ ] Replace the GitHub link `https://github.com/` with your profile.
- [ ] Optional: add a profile photo and project images in `assets/img/`.

## Content rules (important)

- **NDA-safe only.** No proprietary client data (no employer/client project names,
  internal screenshots, ECU part numbers, vehicle model names). Describe method and
  role, not confidential detail.
- No radar/sensor claims that are not verified experience.
