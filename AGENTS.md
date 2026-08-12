# Golden Crane — agent notes

## Live site

- Host: GitHub Pages
- Branch: `main`
- Repo: `https://github.com/WaygoneWilco/golden-crane.git`
- Workflow: `.github/workflows/main.yml`
  - Pushes to `main` trigger a production build and deploy.
  - Hugo is installed by the workflow; no local `go` or `hugo` execution is required to deploy.
- Before changing content or styling, rebuild locally to catch errors:
  - `npm run build` (runs theme CSS generation then `hugo`)
  - `hugo --gc` is also valid for a quick build
- If public output ever looks stale, delete `public/` before rebuilding.

## CLI style

Direct, terse. No preamble, just results.
