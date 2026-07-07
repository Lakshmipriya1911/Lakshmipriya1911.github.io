# Portfolio Site

A single-file static site (`index.html` — no build step, no framework)
built directly from the resume and the three GitHub projects.

## Preview it locally

Just double-click `index.html`, or:
```bash
open index.html          # Mac
```

## Host it for free (recommended: GitHub Pages)

1. Create a new GitHub repo named exactly `Lakshmipriya1911.github.io`
   (must match your GitHub username exactly — this is GitHub's special
   naming convention for a free personal site).
2. Push these files to it:
   ```bash
   cd portfolio-site
   git init
   git add .
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/Lakshmipriya1911/Lakshmipriya1911.github.io.git
   git push -u origin main
   ```
3. Go to the repo → **Settings** → **Pages** (left sidebar) → under "Build and deployment," source should already default to the `main` branch — if not, select it → **Save**.
4. Within a minute or two, your site is live at:
   **https://lakshmipriya1911.github.io**

That URL is free, permanent, and yours to put on your resume/LinkedIn.

## Updating content later

Everything is in `index.html` — the text is plain HTML, so updating a
bullet point, adding a project, or changing a stat is just editing text
in that file, then `git add . && git commit -m "update" && git push`.
GitHub Pages redeploys automatically within a minute of any push.

## Notes

- The "Download Resume" button expects `Lakshmi_Priya_Ramireddy_AI_Engineer_Resume.docx`
  to sit next to `index.html` (already included) — if you update your resume later,
  just replace that file with the same filename.
- All project/GitHub links point to your real, pushed repos
  (`rag-chatbot`, `etl-pipeline`, `cv-pothole-demo`) and the real DOI for
  your published paper — nothing on this page is a placeholder.

