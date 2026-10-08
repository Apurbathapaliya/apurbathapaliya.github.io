# Apurba Deep Thapaliya: personal website

A one-page portfolio built with plain HTML, CSS and JavaScript. No build step, no frameworks.

## Files

- `index.html`: the whole site (styles and scripts are inside this file)
- `assets/Apurba_Deep_Thapaliya_Resume.pdf`: the resume linked from the site
- `.nojekyll`: tells GitHub Pages to serve the files as they are

## Put it online with GitHub Pages

1. Sign in to GitHub and create a new **public** repository named exactly `YOUR-USERNAME.github.io`
   (replace YOUR-USERNAME with your GitHub username).
2. Click **Add file > Upload files** and drag in everything from this folder: `index.html`,
   `README.md`, `.nojekyll` and the `assets` folder. Click **Commit changes**.
3. Go to **Settings > Pages**. Under "Build and deployment", set Source to **Deploy from a branch**,
   branch **main**, folder **/ (root)**, then click **Save**.
4. Wait a minute or two, then open `https://YOUR-USERNAME.github.io`.

Tip: on a Mac, files starting with a dot (like `.nojekyll`) are hidden in Finder. Press
Cmd + Shift + . to show them before dragging. The site still works without it.

## Updating it later

- **New resume:** replace `assets/Apurba_Deep_Thapaliya_Resume.pdf` with a file of the same name.
- **Jobs and bullets:** in `index.html`, search for `const jobs = [`. Each job is one block of text.
- **Skills:** search for `const skillGroups = [`.
- **Colors:** the color values are at the top of the `<style>` section (`--accent`, `--brand`).

After editing, upload the changed file to the same repository. The site updates within a few minutes.
