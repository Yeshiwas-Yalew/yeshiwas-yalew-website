# Yeshiwas Yalew — Personal Website

A responsive, static personal portfolio website built with HTML, CSS, and vanilla JavaScript. No build tools or backend are required.

## Files
- `index.html` — all page content and sections
- `styles.css` — responsive design and visual styling
- `script.js` — mobile navigation and dynamic copyright year
- `assets/` — place your profile photo, CV, and other media here

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser.
3. For a local development server, run `python -m http.server 8000` from this directory and visit `http://localhost:8000`.

## Deploy
### GitHub Pages
1. Create a GitHub repository, for example `yeshiwas-yalew-website`.
2. Upload the contents of this folder to the repository root.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, choose `main` and `/ (root)`, then save.

### Netlify
1. Sign in to Netlify.
2. Choose **Add new site → Deploy manually**.
3. Drag the extracted project folder into the deployment area.

### Render
Create a **Static Site**, connect the repository, and set the publish directory to `.`. No build command is needed.

## Required personalization before publishing
Search `index.html` for `YOUR_EMAIL@example.com` and replace it with your real public email address. Update LinkedIn, Google Scholar, and GitHub links. Confirm the exact employment dates and institutional wording. Add only verified publication metadata and project links.

### Add a profile photo
Put a professional portrait in `assets/profile.jpg`. The current hero uses a designed initials placeholder; to use your portrait, replace the `.profile-placeholder` element in `index.html` with:
`<img class="profile-photo" src="assets/profile.jpg" alt="Portrait of Yeshiwas Yalew">`
Then add this CSS:
`.profile-photo{width:235px;height:285px;object-fit:cover;border-radius:120px 120px 25px 25px;border:1px solid #8bd8cb66;box-shadow:0 30px 80px #0005;z-index:1}`

## Notes
This is a static portfolio website. It does not collect or store visitor data and does not include a contact-form backend. The email link opens the visitor's email application. A working contact form would require a form service or backend.
