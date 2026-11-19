# Personal website (static, GitHub Pages)

Plain HTML/CSS/JS, no build step, no backend, no paid services.

## Files
- `index.html`: the whole site (styles and script included)
- `resume.pdf`: **add this yourself** (resume without phone number)

## Deploy
1. On GitHub, create a **public** repository named exactly `Azamatuz.github.io`.
2. Upload `index.html` and `resume.pdf` (Add file > Upload files > Commit).
3. Repo **Settings > Pages**: Source = "Deploy from a branch", Branch = `main`, folder `/ (root)`. Save.
4. After about a minute the site is live at `https://azamatuz.github.io/`.
5. Update the `url` in the JSON-LD block near the top of `index.html` if your address differs.

## Update content
- Edit text directly in `index.html` on GitHub (pencil icon), then commit.
- **Add a project:** copy one `<div class="card fade">...</div>` block inside the `#work` section and edit it.
- **Add a job:** copy one `<div class="job">...</div>` in `#experience`.
- Keep results honest: only state outcomes you can support.

## Optional later
Add a photo, a custom domain, and a `Selected work` link for each project once you have public links.
