# $UPTOBER

Static site. No build step.

## Publish on GitHub Pages
1. Create a new public repository on GitHub.
2. Upload everything in this folder (index.html, assets/, .nojekyll).
3. Settings → Pages → Source: "Deploy from a branch" → Branch: main, folder: / (root) → Save.
4. After about a minute the site is live at https://YOUR-USERNAME.github.io/REPO-NAME/

## Edit the contract address and X link
Open index.html and find the CONFIG block near the top of the main script:

    const CONFIG = {
      ca: "",                 // contract address
      x: "https://x.com/",    // your X profile
      ticker: "$UPTOBER",
    };
