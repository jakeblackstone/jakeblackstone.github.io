# jakeblackstone.github.io

Personal portfolio site. Built with [Astro](https://astro.build) and vanilla TypeScript. Deployed to GitHub Pages via GitHub Actions.

## Editing content

All prose lives in `src/content/`. Edit the Markdown files directly:

| File | What it controls |
| ---- | ---------------- |
| `src/content/about.md` | Bio paragraph and interests list |
| `src/content/resume.md` | Experience, Skills, Education sections |

Push to `main` to redeploy.

## Swapping images

Drop replacements into `public/images/`. Expected filenames:

| File | Used for |
| ---- | -------- |
| `headshot.jpg` | Portrait (displayed at 240×240) |
| `photo-1.jpg` | Photo grid |
| `photo-2.jpg` | Photo grid |
| `photo-3.jpg` | Photo grid |

Prefer square crops. Push to `main` to redeploy.

## Swapping the resume PDF

Replace `public/resume.pdf` with the updated file. Filename must stay `resume.pdf`.

## Deploying

Push to `main`. The Actions workflow builds and deploys automatically (~2 min). Watch progress in the **Actions** tab on GitHub.

## Local dev

```sh
npm install
npm run dev      # http://localhost:4321
npm run build    # production build → ./dist/
npm run preview  # preview the build locally
```
