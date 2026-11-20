# Ashik Biswas — 3D Portfolio

A personal, responsive 3D portfolio website for Ashik Biswas. It features a cosmic Three.js scene, interactive 3D MacBook visualization, glassmorphism UI, project showcase, skills, education, and social links.

## Files

- `index.html` — the complete website
- `ashik-profile.jpg` — profile photo used by the website
- `.nojekyll` — disables GitHub Pages Jekyll processing

## Run locally

You can open `index.html` directly in a browser. For the best local development experience, use VS Code with the Live Server extension.

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `ashikbiswas01.github.io` (for a user-site URL) or `my-portfolio`.
2. Upload **all three files** from this folder to the repository root. Keep the image filename exactly `ashik-profile.jpg`.
3. Commit the files to the `main` branch.
4. Open the repository's **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then click **Save**.
7. Wait for GitHub Pages to publish the site. The published URL will appear in the Pages settings.

## Important

- Keep `index.html` and `ashik-profile.jpg` in the same folder (repository root), otherwise the profile photo will not load.
- The design loads Tailwind CSS, Font Awesome, Google Fonts, and Three.js from CDNs, so an internet connection is needed for those external assets.
- Check every social profile URL and contact detail before making the repository public.
- GitHub Pages publishes the website source publicly when the repository is public.
