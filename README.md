# Altavento Tempesta · website files

Static build of the site. Designed by WorksByJem.

## Put it live on GitHub Pages

1. Create a new GitHub repo (for example `altavento-tempesta`).
2. Upload everything in this folder to the repo root, including the hidden `.nojekyll` file and the `_next` folder.
3. Go to **Settings → Pages**. Under **Source** choose **Deploy from a branch**, then pick `main` and `/ (root)`. Save.
4. After a minute the site is live at `https://<your-username>.github.io/<repo-name>/`

## Cloudflare Pages

Create a Pages project, choose **Upload assets**, and drop this whole folder in. No build step is needed.

## Notes

* Open it through a web host (GitHub Pages, Cloudflare, or a local server such as `npx serve .`). Double clicking `index.html` from your computer will not load the scripts.
* To change text, colours or links, edit the source project (`data/siteData.ts`) and rebuild.
