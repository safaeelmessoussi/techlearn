# iTraining

Free, hands-on training programs that build practical technical skills in:

- **How a Computer Really Works** (start here, zero knowledge needed)
- **Computer Hardware & IT Support**
- **Software Development**
- **Computer Networking**
- **Cybersecurity**
- **Cloud Computing**

Each program has six modules. Every module covers its key topics, ends with a hands-on lab, and includes a quick knowledge check. Learners can filter programs by level, follow career paths, and track their progress (saved in the browser).

### How a Computer Really Works (`foundations.html`)

A full-width illustrated page for high-school beginners. The computer is drawn as a restaurant kitchen (CPU = chef, RAM = countertop, storage = pantry, cooler = extractor hood, GPU = plating team, OS = manager). Eleven chapters follow the data with animated flows and live simulations: inputs/outputs sorting, a heat simulator, creating folders and files with the mouse or a practice PowerShell terminal, typing into Word with a power-cut test, a text-to-binary translator, saving, reopening down to the pixels, and an HTML editor rendered on the drawn monitor. Future layers (security, networks, cloud, AI) will build on the same drawing.

## Stack

Static pages (`index.html`, `foundations.html`) with no build step and no dependencies. `_headers` adds basic security headers on Cloudflare Pages.

## Deploy on Cloudflare Pages

1. In the Cloudflare dashboard, go to **Workers & Pages → Create → Pages → Connect to Git**.
2. Select this repository and the `main` branch.
3. Framework preset: **None**. Build command: *(leave empty)*. Build output directory: `/`.
4. Name the project `itraining` to get `itraining.pages.dev`.

Every push to `main` redeploys the site automatically.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```
