# Krishna Prosad Mondal - academic website

A responsive, standalone HTML/CSS/JavaScript website for geospatial research, publications, projects, teaching, and collaboration. No installation or framework is required to use the delivered website.

## Publish on GitHub Pages

1. Sign in to GitHub and create a public repository named `YOUR-USERNAME.github.io`, replacing `YOUR-USERNAME` with your actual username. If that repository already exists, save a backup before updating it.
2. Extract `Krishna-Mondal-GitHub-Website.zip`. Open the extracted folder and upload its contents to the repository using **Add file → Upload files**. `index.html` must sit at the repository root beside the `assets`, `research`, and other folders. Do not upload the ZIP itself or an extra enclosing folder. Commit the upload to `main`.
3. Open **Settings → Pages**. Under Source, select **Deploy from a branch**. Choose **main** and **/(root)**, then save.
4. Visit `https://YOUR-USERNAME.github.io/` after GitHub finishes publishing. This may take up to 10 minutes.

Official guide: https://docs.github.com/en/pages/quickstart

## What is included

- `index.html`: homepage and professional background
- `research/index.html`: research themes
- `projects/index.html`: selected projects and professional work
- `publications/index.html`: selected publication records and DOI links
- `teaching/index.html`: teaching and training
- `portfolio/index.html`: applied methods and experience
- `cv/index.html`: selected CV with a Print / save as PDF button
- `collaborate/index.html`: collaboration and student enquiries
- `contact/index.html`: professional contact details and profiles
- `assets/style.css`: typography, colours, layout, responsive and print styles
- `assets/main.js`: mobile menu and print button
- `assets/river-delta.webp`: original generated background artwork
- `assets/favicon.svg`: initial-based icon
- `404.html`: missing-page message
- `.nojekyll`: bypasses Jekyll processing when included in the upload

## Edit your website

Open an HTML file in a text editor and change its text. On GitHub, open the file and choose the pencil icon to edit it, then commit. Shared navigation and footer markup is repeated in each page, so update all pages when changing either.

Change the colour variables at the beginning of `assets/style.css` to adjust the theme. To replace the hero artwork, use a wide image and retain the filename `river-delta.webp`, or update the image source in `index.html`.

The CV is a newly prepared summary, not an imported official CV. Use its print button to save a PDF. If you prefer your existing full CV, add it as `assets/files/cv.pdf` and add a link to it in `cv/index.html`. Confirm your current job title, PhD enrollment details, contact details, and project descriptions when you update your profile.

Google Scholar, ResearchGate, LinkedIn, and email links are included from your shared professional details. No GitHub profile link has been guessed. Add your own once your username is known.

Project summaries describe work and research interests; no project datasets, confidential client outputs, results maps, or downloadable work samples were supplied. The portfolio therefore presents methods and linked project descriptions. Add shareable work samples when available.

The background is original AI-generated, Earth-observation-inspired artwork. It is not an actual satellite image or an analytical map. No portrait has been fabricated. GeoAI and agent-based modelling are identified as developing interests.

## Publication sources

Selected works were checked against publisher and journal records. The list is selective and may not include every paper or preprint.

- https://doi.org/10.1007/978-3-031-93177-2_3
- https://doi.org/10.1016/B978-0-443-31568-8.00055-6
- https://doi.org/10.1007/s10393-025-01733-x
- https://doi.org/10.59185/jgs.v1i1.269
- https://doi.org/10.1007/978-981-96-7488-6_9
- https://doi.org/10.1002/9781394235278.ch2
- https://doi.org/10.1016/j.uclim.2024.102263
- https://doi.org/10.1016/B978-0-443-18515-1.00004-6
- https://doi.org/10.3329/jscitr.v5i1.74011
- https://doi.org/10.1016/j.joclim.2023.100203

Publication titles link to their source records. The list is selective. Professional background and project summaries were drafted from the information shared in the conversation.

Design inspiration: https://hc2x.github.io/join/ - the website uses original wording and an independently created design.

## Local viewing

Open `index.html` in your browser. The main pages use relative links so they can be opened locally and published at a GitHub Pages root or project path. The custom 404 homepage link assumes the requested `username.github.io` root site; adapt it if publishing under a project subdirectory.

## Source checkout note

In the preview source checkout, the public website files are stored under `dist/`; the GitHub ZIP puts these files at its root for direct upload. `.openai/hosting.json` belongs only to the private preview and is excluded from the GitHub package.
