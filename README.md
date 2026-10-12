# Creastor Studio — GitHub Pages Website

A responsive, dark neon studio website made with plain HTML, CSS, and JavaScript. No build tools, frameworks, or paid hosting are required.

## Files

- `index.html` — page content and game cards
- `styles.css` — layout, colors, responsive design, and CSS artwork
- `script.js` — mobile navigation and current year
- `assets/favicon.svg` — browser tab icon

## Publish on GitHub Pages

1. Sign in to [GitHub](https://github.com/).
2. Create a **public** repository. For a personal site, name it `YOUR-USERNAME.github.io` (replace `YOUR-USERNAME` with your GitHub username).
3. Upload the contents of this folder to the repository root. Make sure `index.html` is at the root, not inside another folder.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then click **Save**.
7. Wait for the deployment, then open `https://YOUR-USERNAME.github.io/`.

If you use a project repository with another name, such as `creastor-studio`, the URL will usually be `https://YOUR-USERNAME.github.io/creastor-studio/`.

## Customize before launch

Search `index.html` and replace the following sample content:

- **Project titles and descriptions:** `PROJECT: LAST STOP`, `NEON RUNNER`, `UNKNOWN WILDS`
- **Game links:** change each card's `href` to your real game page. Remove `data-placeholder-link` when you replace the placeholder link, otherwise the demo behavior will intercept clicks.
- **Contact email:** replace `hello@creastorstudio.com` with an email address you actually use.
- **Social links:** update the GitHub and itch.io links in the footer to your real profiles.
- **Studio location:** change `DELHI, INDIA · WORKING WORLDWIDE` if you want different wording.

The game artwork is made in CSS, so the site works without external screenshots. To use real screenshots later, add image files in `assets/` and replace the relevant `.game-art` artwork in `index.html` with an `<img>` element. Use optimized WebP images for faster loading.

## Test locally

Double-click `index.html` to preview in a browser, or run a local static server from this folder. Check the page at both desktop and mobile widths before publishing.

## License

You may customize and use this starter site for Creastor Studio. Replace sample project details with accurate information before launch.
