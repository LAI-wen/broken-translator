# GitHub Pages Deploy Folder

This folder is the static build of the Broken Translator website.

## What to upload

Upload the contents of this folder to a GitHub repository branch that GitHub Pages serves, or copy these files into the repository root if you want to deploy from the root:

- `index.html`
- `assets/`
- `.nojekyll`

Do not upload `node_modules/`, `src/`, `dist/`, research notes, or the Word report unless you also want the source materials public.

## GitHub Pages settings

In the repository:

1. Open `Settings`.
2. Go to `Pages`.
3. Set `Source` to `Deploy from a branch`.
4. Choose the branch containing these files.
5. Choose `/ (root)` as the folder.

The site uses relative asset paths, so it works on both user pages and project pages.

## Rebuild

From the project root:

```bash
npm run build
```

Then copy the new `dist/index.html` and `dist/assets/` into this folder.
# broken-translator
