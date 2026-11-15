# Irfan Murtaza — Personal Portfolio (GitHub Pages)

This is a lightweight, responsive, static portfolio. No build step, Node.js dependency, or backend is required.

## Preview locally

```bash
python3 -m http.server 8000
```

Open http://localhost:8000 to preview.

## Deploy to GitHub Pages

1. Back up your current repository.
2. Copy the files from this folder into the repository root (`IrfanMurtaza93/IrfanMurtaza93.github.io`), keeping `index.html` at the root.
3. `git add . && git commit -m "Refresh backend engineering portfolio" && git push origin master` (use `main` if your repository uses main).
4. In **Settings → Pages**, confirm deployment from the correct branch and root folder.
5. Visit https://irfanmurtaza93.github.io/ after GitHub Pages finishes publishing.

## Site map
- `index.html` — hero, overview, selected projects, call to action
- `projects.html` — project case studies and other work
- `resume.html` — career timeline and skills
- `contact.html` — email / social links
- `css/site.css` — all styling
- `js/site.js` — mobile navigation behavior
- `assets/Irfan_Murtaza_Resume.pdf` — downloadable CV

## Content maintenance
- Update the PDF in `assets/` whenever your CV changes.
- Update employment dates and skill descriptions in `resume.html`.
- Use only verified project metrics; 30+ integrations is documented. The 1M-user figure is an **architecture planning target**, not claimed actual user volume.
- `assets/profile_5.png` is the original portrait from the provided website.
- The contact page uses `mailto:` links, not a form, so no external form service is needed.
- All pages use relative local links, so they work at the domain root.

## Before publishing
Please review content for confidentiality (especially client/product names), verify employment dates, and replace the resume PDF if you have a newer version.
