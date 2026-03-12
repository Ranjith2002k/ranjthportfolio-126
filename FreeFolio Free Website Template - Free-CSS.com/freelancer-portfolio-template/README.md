# Freelancer Portfolio Template (local run instructions)

This is a static HTML/CSS/JS portfolio template. There are no runtime Python or backend dependencies required to view the site — you can open the `index.html` file in a browser. Below are recommended ways to run the project locally and developer conveniences.

## Run locally (three easy options)

1) Open in your browser

  - Double-click `index.html` or open it from your browser (`File → Open File...`).

2) Using Python 3 (built-in, no extra packages needed)

  - From the template folder run:

  ```powershell
  cd "c:\Users\DELL\OneDrive\Desktop\ranjthportfolio-126\FreeFolio Free Website Template - Free-CSS.com\freelancer-portfolio-template"
  python -m http.server 8080
  ```

  - Then open http://localhost:8080 in your browser.

3) Using npm and a lightweight static server (recommended if you use Node/npm already)

  - Install dependencies once:

  ```powershell
  cd "c:\Users\DELL\OneDrive\Desktop\ranjthportfolio-126\FreeFolio Free Website Template - Free-CSS.com\freelancer-portfolio-template"; npm install
  ```

  - Start the server:

  ```powershell
  npm start
  ```

  - Then open http://localhost:8080

## Notes

- This is a static template (HTML/CSS/JS). There are no server-side components in this project by default.
- `requirements.txt` intentionally contains no Python packages because the site is static. See that file for details.

## Deploying to Vercel

This project is ready for Vercel (static site) deployments. You can deploy either via the Vercel web UI (connect your GitHub repo) or with the Vercel CLI.

Web UI (recommended):

- Push the repo to GitHub (you've already done this).
- Go to https://vercel.com, sign in with GitHub, click "New Project", pick your repo and import it.
- For a static site, Vercel usually detects the right settings automatically. Set the "Build Command" to empty and "Output Directory" to `/` if prompted.

Vercel CLI (one-time deploy from your machine):

```powershell
npm i -g vercel
vercel login
cd "c:\Users\DELL\OneDrive\Desktop\ranjthportfolio-126\FreeFolio Free Website Template - Free-CSS.com\freelancer-portfolio-template"
vercel --prod
```

After the first deploy, Vercel links the project to your Git provider and will auto-deploy on pushes to the connected branch.

I've also added an optional `vercel.json` in the repo to explicitly tell Vercel to treat the project as a static site.

## Maintainer suggestions (optional)

- If you want live reload while editing, consider installing `live-server` or a similar tool and updating the `package.json` scripts.

---
Generated/updated by repository maintenance script on 2026-03-12.
