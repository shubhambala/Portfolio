# Shubham Balakrishnan — Resume Website

A single-page, self-contained resume site: hero with photo, animated stats,
experience timeline with click-to-expand detail, skills & certifications,
education, and contact — built for recruiters/hiring managers to skim fast.

## Files

- `Shubham-Balakrishnan-Resume.html` — the standalone, offline-ready site.
  All fonts, images, and the downloadable resume PDF are bundled inside this
  one file. Open it directly in any browser — no server or build step needed.
- `Resume.dc.html` — the editable source (Design Component). Keep this if you
  want to make future edits in this tool; it references `assets/shubham.png`
  and `uploads/profile.pdf` as separate files.

## Hosting on GitHub Pages

1. Create a repo (e.g. `yourname.github.io` or any repo name).
2. Add the standalone file to the repo root and rename it `index.html`:
   ```
   cp "Shubham-Balakrishnan-Resume.html" index.html
   ```
3. Commit and push to the `main` branch.
4. In the repo's **Settings → Pages**, set the source to the `main` branch,
   root folder.
5. Your site will be live at:
   - `https://yourname.github.io` (if the repo is named `yourname.github.io`), or
   - `https://yourname.github.io/repo-name` (for any other repo name).

That's it — no build tools, no dependencies, no separate asset uploads
required since everything is inlined in the one HTML file.

## Making edits later

- **Text/content:** open `Shubham-Balakrishnan-Resume.html` in a code editor
  and search for the copy you want to change (it's plain HTML/JS, human
  readable).
- **Design changes:** easier to make in `Resume.dc.html` (the original
  editable source), then re-export to standalone HTML.
- **Resume PDF:** the Download button points at the bundled copy of your
  resume PDF. To update it, replace `uploads/profile.pdf` in the source
  project and re-export.

## Contact info shown on the site

- Email: shubham.bala@gmail.com
- Phone: +91 63629 95065
- LinkedIn: linkedin.com/in/shubhambala
