# kraft-workshop-slides

Rendered Reveal.js bundle for the **"Your AI Workflow Sucks? It's a Skill Issue"** workshop.

Source lives in [`dracz-fl/kraft-ws`](https://github.com/dracz-fl/kraft-ws) (private). This repo only holds the published export so it can be served via GitHub Pages.

Live: https://dracz-fl.github.io/kraft-workshop-slides/

## Updating

Re-export from Obsidian, then from the source repo run:

```sh
./scripts/deploy-slides.sh
```

That script copies `export/workshop/` and `assets/` into this repo, commits, and pushes.
