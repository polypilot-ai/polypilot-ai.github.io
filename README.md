# PolyPilot AI Pages

Static, versioned assets and mini‑sites served via **GitHub Pages** for the PolyPilot organization.

**Live site:** https://polypilot-ai.github.io/

## What this repo is for
- **Brand & press assets** (logos, downloads): [`/brand/`](brand/)
- **Email signature icons & logos**: [`/email-signature/`](email-signature/)
- Future: lightweight **project/paper sites**, **API reference** (ReDoc/Swagger), and **developer docs**.

## Structure
```
/brand/               - logos, press kit (public)
  index.html
/email-signature/     - 24px PNG icons + logo for email signatures
index.html            - landing page for the org site
.nojekyll             - bypasses Jekyll; serve raw static files
```

## How it deploys
This is an **organization site** (`polypilot-ai.github.io`) publishing from **`main` at the repository root**.
Any commit to `main` deploys the site (Settings → Pages → **Deploy from a branch: main / root**).

## Usage & rights
Unless otherwise noted, brand marks and downloads are © PolyPilot.  
Do not alter or redistribute brand assets without written permission from PolyPilot.

## Contact
**Website:** https://polypilot.ai/  
**Email:** contact@polypilot.ai
