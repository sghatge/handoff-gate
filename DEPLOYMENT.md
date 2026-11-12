# Handoff Gate — GitHub Pages deployment

## Required repository structure

```text
handoff-gate/
├── .nojekyll
├── LICENSE
├── README.md
├── index.html
├── demo/
│   └── index.html
└── carousel/
    └── index.html
```

## Publish

1. Extract this package.
2. Upload all files and folders inside it to the root of `sghatge/handoff-gate`.
3. Commit the changes to `main`, preserving the existing MIT license.
4. Open repository **Settings → Pages**.
5. Set **Source** to **Deploy from a branch**, branch to `main`, folder to `/(root)`.
6. Save and wait for the Pages deployment workflow to succeed in **Actions**.

## Verify

- https://sghatge.github.io/handoff-gate/
- https://sghatge.github.io/handoff-gate/demo/
- https://sghatge.github.io/handoff-gate/carousel/

Do not announce the site as live until all three pages load and the demo controls and carousel navigation have been manually tested.
