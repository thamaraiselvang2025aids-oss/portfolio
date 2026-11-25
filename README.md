# Thamarai Selvan G: 3D Portfolio
Static site (HTML, CSS, JS, Three.js via cdnjs). No backend, no API keys.

## Deploy to GitHub Pages
```bash
git clone https://github.com/thamaraiselvang2025aids-oss/portfolio.git && cd portfolio
git checkout -b backup-old-site && git push -u origin backup-old-site   # backup current site
git checkout -b 3d-portfolio
# copy this folder's contents into the repo, then:
git add . && git commit -m "3D portfolio" && git push -u origin 3d-portfolio
git checkout main && git merge 3d-portfolio && git push
```
Then Settings > Pages > Source: Deploy from branch > `main` / root.
Live at https://thamaraiselvang2025aids-oss.github.io/portfolio/ (allow 1-2 minutes).

## Placeholders to fill
SELFIE evaluator certificate, project screenshots, CodeNova / DSOC Merit / Bharat Academix / Retrofest workshop certificates.

## Troubleshooting
Blank 3D background: check network access to cdnjs.cloudflare.com (the page still works without it). 404 on images: keep the assets/ folder next to index.html.
