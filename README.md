# Rento — Static Business Website

A responsive, minimal business website built with plain HTML, CSS, and JavaScript. No build tools or framework required.

## Files

- `index.html` — page structure and content
- `style.css` — layout, styling, and responsive breakpoints
- `script.js` — mobile navigation, current year, and contact email interaction

## Preview locally

1. Download and unzip the project.
2. Open `index.html` in your browser.

For a local development server, you can use the VS Code **Live Server** extension.

## Publish with GitHub Pages

1. Sign in to GitHub and create a new repository, for example `rento-website`.
2. Upload `index.html`, `style.css`, `script.js`, and `README.md` to the repository root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Wait for GitHub Pages to publish. Your site URL will appear in the Pages section.

## Before publishing

- Replace `hello@rento.example` in `script.js` and `index.html` with your real business email.
- Update the sample category names, descriptions, and images to match your rental business.
- Replace the example Unsplash images if you have your own brand photography.
- Add your real social links, address, phone number, and business policies if needed.

## Notes

- This is a front-end static site. The contact form opens the visitor's default email application; it does not save enquiries to a database.
- Google Fonts and the sample Unsplash images load from external services, so an internet connection is needed for those assets.
- No backend, API keys, or paid hosting are required for GitHub Pages.
