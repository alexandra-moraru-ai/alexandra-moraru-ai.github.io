# Alexandra Moraru: one-page résumé site

A static site for GitHub Pages. No build step, no server, no tracking, no cookies.

```
index.html      all page content
styles.css      all styling
assets/         portrait and favicon
```

## Publish on GitHub Pages

1. Create a public repository. Name it `<username>.github.io` for the address `https://<username>.github.io/`, or any other name for `https://<username>.github.io/<repository>/`.
2. Upload `index.html`, `styles.css`, `README.md` and the `assets` folder to the repository root on the `main` branch.
3. Go to Settings → Pages → Build and deployment. Choose "Deploy from a branch", then `main` and `/ (root)`. Save.
4. Wait a minute or two, then open the URL shown in the Pages settings. Turn on "Enforce HTTPS" if offered.
5. Check the page on desktop and mobile: every navigation link, all three booking buttons, the LinkedIn link, the publication link and the portrait.

## Edit the content

All text lives in `index.html`. Each section is marked with a comment such as `<!-- EXPERIENCE -->`. Edit the text between the tags, commit to `main`, and the site redeploys automatically.

- **Booking link:** search for `calendly.com`. It appears three times (navigation, hero, contact), each marked `BOOKING LINK`. Change all three together.
- **Email address:** search for `mailto:`. It appears twice (contact, footer).
- **LinkedIn link:** search for `linkedin.com`. It appears twice (contact, footer).
- **Add a role:** copy one `<article class="role">` block in the Experience section and paste it above the others.
- **Portrait:** replace `assets/alexandra-portrait.webp` with a new 800 × 1000 px image of the same name.
- **Colours:** change the variables at the top of `styles.css`.

## Before going live

- Confirm the Kazient trainee description matches the work actually started.
- Confirm the Privacy Pros Academy bullets are correctly attributed to that role.
- Decide whether to keep the "In preparation: IAPP AIGP exam" entry. It is marked OPTIONAL in `index.html`.
- This repository is public, including its history. Keep private drafts, unpublished research and sensitive documents out of it.
