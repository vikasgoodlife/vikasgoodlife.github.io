```markdown
# Lumia UPVC Profiles — Static Site (W3.CSS)

This repository contains a simple static website built using W3.CSS for Lumia, an importer and wholesale distributor of UPVC profiles.

Pages:
- index.html — Home / overview
- about.html — About us, mission and values
- profiles.html — Profiles available with brief specs
- branches.html — Branch locations and contact details
- contact.html — Contact form (Formspree integration recommended)

Primary contact details (update these in the files if you want different values):
- Head Office: 1804, 13th Cross Sector 1, HSR Layout, Bangalore
- Mobile: +91 9980063411
- Email: sales@lumiaprofiles.com

Deployment:
1. Push these files to the `main` branch (or `gh-pages`) of your GitHub repository `vikasgoodlife/vikasgoodlife.github.io`.
2. For GitHub Pages, if the repo name is `vikasgoodlife.github.io`, GitHub will serve `index.html` from the main branch automatically.
3. Replace placeholder images with real product photos or CAD snapshots.
4. Integrate the contact form:
   - Recommended: Use Formspree (https://formspree.io) or a simple server endpoint to collect submissions.
   - For Formspree: create a form there, copy the endpoint URL, and replace the `action` attribute in contact.html.

Customization:
- Update colors by changing W3.CSS classes or adding a small custom stylesheet.
- Add downloadable PDF drawings by linking to files in an `assets/` directory.

If you'd like, once the repository has an initial branch I will push these files to a feature branch and open a PR with the changes.