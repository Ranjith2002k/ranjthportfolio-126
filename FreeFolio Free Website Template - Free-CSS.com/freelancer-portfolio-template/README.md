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

## Maintainer suggestions (optional)

- If you want live reload while editing, consider installing `live-server` or a similar tool and updating the `package.json` scripts.

---
Generated/updated by repository maintenance script on 2026-03-12.
