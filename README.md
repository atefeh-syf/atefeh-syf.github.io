# Atefeh Seyfi — Personal Landing Page

A static personal landing page built with plain HTML, CSS and JavaScript. It is ready for GitHub Pages and has no build step.

## Files

- `index.html` — page structure and content
- `styles.css` — responsive visual design
- `script.js` — mobile menu, scroll reveals and navigation state
- `assets/atefeh-seyfi.jpg` — profile photo
- `assets/Atefeh-Seyfi-Resume.docx` — downloadable resume

## Run locally

You can double-click `index.html`, or run a small local server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload everything in this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your main branch and the `/ (root)` folder.
6. Save. GitHub will show the public URL after deployment.

## Customize

The main colors are defined at the top of `styles.css` under `:root`.
Contact links and text can be edited directly in `index.html`.
