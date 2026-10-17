# Never Seen Before website

## Pages
- `index.html` — Home
- `roster.html` — 5 player + 5 creator placeholders
- `foundation.html` — NSB founders
- `sponsors.html` — 3 sponsor placeholders with copy buttons
- `contact.html` — Formspree contact form
- `style.css` — Shared black/gold responsive theme
- `script.js` — Copy-to-clipboard and contact form status
- `images/` — Branding and future images

## Publishing
Upload all files and the `images` folder to the root of a GitHub Pages repository. Set GitHub Settings > Pages to deploy from the appropriate branch.

## Editing the roster
Open `roster.html`. Each card has an HTML comment identifying it. Change placeholder names and descriptions. Replace image placeholder `<div>` contents with `<img src="images/player-1.png" alt="Player Name">` (or creator-1.png). For tracker and social buttons, replace `href="#"` with your URL, remove `disabled` from class and remove `aria-disabled="true"`; add `target="_blank" rel="noopener noreferrer"` for external links.

## Editing sponsors
Open `sponsors.html`. For each sponsor, replace its placeholder div with the `<img>` snippet shown in the nearby comment, then add the matching `sponsor-1.png` etc. to `images/`. Replace `YOURCODE1` in **both** the displayed `<span>` and the button's `data-copy` attribute.

## Contact form
Formspree endpoint `https://formspree.io/f/xnpjwkoj` is already configured. Verify and activate the form in your Formspree account, including the recipient email. The form uses browser validation, a honeypot, and a success/error message; spam prevention and filtering should also be configured in Formspree. For full behavior, preview via a web server or GitHub Pages rather than `file://`.

## Images
`images/nsb-logo.png` and `images/nsb-banner.png` are your uploaded assets.
