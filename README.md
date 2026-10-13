# Rahi Kulkarni: personal website

A one-page static website. There's no build step: GitHub Pages serves these files as they are.

## What's in this folder
- `index.html`: the whole page (layout, styles and content)
- `images/`: photos, resized and with location data removed
- `favicon.svg`: the small "RK" icon shown in the browser tab
- `.nojekyll`: an empty file that tells GitHub Pages to publish the files exactly as they are. It's hidden on a Mac; press Cmd+Shift+. in Finder to see it.

## Publishing on GitHub Pages
The full steps are in the conversation where this site was built. In short:
1. Create a public repository named `<username>.github.io`.
2. Upload everything in this folder to the root of that repository.
3. In Settings > Pages, deploy from the `main` branch, `/ (root)` folder.

## Making changes later
Edit `index.html` on github.com: open the file, click the pencil icon, change the text, then click "Commit changes". The live site updates within a minute or two.
