# iTraining

Free, hands-on training programs that build practical technical skills in:

- **Computer Hardware & IT Support**
- **Software Development**
- **Computer Networking**
- **Cybersecurity**
- **Cloud Computing**

Each program has six modules. Every module covers its key topics, ends with a hands-on lab, and includes a quick knowledge check. Learners can filter programs by level, follow career paths, and track their progress (saved in the browser).

## Stack

A single static page (`index.html`) with no build step and no dependencies. `_headers` adds basic security headers on Cloudflare Pages.

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
