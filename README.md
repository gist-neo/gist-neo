# NEO Lab GitHub Pages Starter

A dependency-free static website structured from the public NEO Lab Google Sites layout.

## Quick start
1. Create a GitHub repository.
2. Upload every file in this folder to the repository root.
3. In **Settings → Pages**, select **GitHub Actions** as the source.
4. Push to `main`. The included workflow deploys the site. All links are relative, so both user sites and project sites work without editing a base URL.

## Editing content
Structured records are in `/data/*.json`. The current HTML is pre-rendered for maximum compatibility. When records change, edit the corresponding HTML or connect the JSON files through JavaScript.

## Images
Google Sites blocks automated redistribution of many original image files. Local SVG placeholders are included so the site never breaks. Replace them with original photos while keeping the filenames:
- Professor: `assets/images/common/professor.svg`
- Members: `assets/images/members/01.svg` ...
- Research graphics: `assets/images/research/*.svg`

## Color
The point color is `--gist: #C51A2E` in `assets/css/style.css`, selected to reflect the red element of the official GIST identity. Change this single variable to update the entire site.

## Source structure
The navigation and public content were organized from the public website at `https://sites.google.com/view/gist-dhkang`. Review all imported text, names, semesters, and publication metadata before final launch.
