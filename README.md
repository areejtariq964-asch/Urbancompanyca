# Urban Company Canada — static website prototype

This is a static website. It uses plain HTML, CSS, and JavaScript. There is no build step.

## Files

- `index.html` — page structure
- `styles.css` — layout, colours, and responsive styling
- `app.js` — service data, page navigation, search, and prototype interactions
- `.nojekyll` — tells GitHub Pages to serve files as static assets

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `urban-company-canada`.
2. Add all four files from this folder to the repository root. `index.html` must be at the root.
3. Commit the files to the `main` branch.
4. In GitHub, open the repository’s **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then save.
7. Wait for the Pages deployment. Its URL will appear on the Pages settings screen. For a project repository it is usually `https://YOUR-USERNAME.github.io/urban-company-canada/`.

GitHub Pages serves published sites publicly. Do not include private data in this repository. See [GitHub’s Pages setup guide](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Edit the site

Edit the `services` array in `app.js` to add or change services. The city list is near it. Keep the three files together in the repository root.

Prices, reviews, and launch cities are sample content. Booking, account, professional, support, and newsletter forms are demonstrations; they do not send messages, take payments, create accounts, or dispatch service providers. Connect a backend and replace sample content before real use.

This is an independent prototype, not an official Urban Company website. Use official company branding or claim affiliation only if authorized.
