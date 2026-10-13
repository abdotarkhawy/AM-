# AM Dental Clinic - Content Collection

Static site: `index.html` + `data.json` + `media/` (all photos and videos).

## Publish (GitHub Pages)
1. Upload everything in this folder to the repository root (keep the `media` folder as is).
2. Settings > Pages > Deploy from a branch > `main` / `(root)` > Save.

## Edit the site from the web page
1. GitHub > Settings > Developer settings > Personal access tokens > Fine-grained tokens > Generate new token.
2. Repository access: "Only select repositories" > pick this repository.
3. Repository permissions > **Contents: Read and write**. Set an expiration. Generate and copy the token.
4. Open the site address followed by `#edit`, press the lock button, paste the token.
5. An "Edit" button appears. Every save is committed to this repository (data.json and media/) and the public site updates after about 1-2 minutes.

Never share the token. If it leaks, delete it from GitHub settings.
