# Joshua G. Ramos — Personal Portfolio

A responsive, dark-blue student portfolio website made with plain HTML, CSS, and JavaScript.

## Files
- `index.html` — page content and sections
- `style.css` — colors, layout, responsive mobile styles
- `script.js` — mobile navigation and current footer year

## Before publishing
1. Open `index.html`.
2. In the Contact section, replace `YOUR_EMAIL@example.com` with your real email.
3. Replace the GitHub and Facebook placeholder links with your own profile URLs.
4. Review the Skills section and remove any technology you have not used or cannot explain.
5. Update the project description so it accurately matches your RWIA Checker implementation.
6. The project dashboard image is an illustrative CSS mockup, not a screenshot from the actual app.

## Publish using Vercel (phone or laptop)
### Easiest route: GitHub + Vercel
1. Extract the ZIP file.
2. Sign in to GitHub and create a new repository, for example `joshua-portfolio`.
3. Upload `index.html`, `style.css`, and `script.js` to the repository root (not inside an extra folder).
4. Sign in to Vercel using your GitHub account.
5. Choose **Add New → Project**, then import `joshua-portfolio`.
6. For a plain HTML/CSS/JS site, no build command is needed. Leave the framework preset as **Other** if asked, and deploy.
7. Open the Vercel URL and test the page on both mobile and desktop.

### Alternative: Vercel CLI (laptop)
If Node.js is installed, extract the folder and run:
```bash
cd joshua_portfolio
npx vercel
```
Follow the prompts. For a public production deployment, run:
```bash
npx vercel --prod
```

## Notes
- This is a static website. It does not have a backend or a working contact form.
- External Google Fonts are used for typography; system fonts remain as fallback.
