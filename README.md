# Diana's Purple + Black Portfolio

A simple, editable, multi-page static HTML portfolio suitable for GitHub Pages. No frameworks or build tools needed.

## Pages
- `index.html` — homepage
- `projects.html` — project portfolio
- `services.html` — services
- `about.html` — bio and social links
- `contact.html` — email contact form
- `style.css` — all colors, layout, and responsive styles
- `script.js` — copyright year and mailto contact form
- `assets/` — your images

## Customize
1. Replace `YOUR_USERNAME`, `YOUR_HANDLE`, and `YOUR_EMAIL@example.com` in the HTML files. Also edit `CONTACT_EMAIL` in `script.js`.
2. Change colors in the `:root` section of `style.css`.
3. Put images in `assets/` and uncomment the sample `<img>` tags inside `.thumb` blocks. Replace each filename with your actual image filename.
4. Edit project descriptions and status labels to reflect what is actually built.
5. The contact form uses `mailto:` (opens the visitor's email app). It does not send messages automatically; use Formspree or another service later if you want direct submissions.

## Publish on GitHub Pages
1. Create a public GitHub repository (for example `portfolio`).
2. Upload all these files to the repository root, including the `assets` directory.
3. In repository **Settings → Pages**, select **Deploy from a branch**, then choose `main` and `/ (root)` and save.
4. Visit the GitHub Pages URL shown in Settings once deployment finishes.

Tip: For a personal root URL (`username.github.io`), name the repository `username.github.io`.
