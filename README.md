# Handoff Gate

A deterministic, policy-based checkpoint between an AI planning agent and campaign activation.

**GO · HOLD · BLOCK**

Every check is named. Every HOLD names the person who can clear it. Every verdict is fingerprinted so the evaluated package and policy version can be audited.

## Live pages

- [Project homepage](https://sghatge.github.io/handoff-gate/)
- [Interactive Handoff Gate demo](https://sghatge.github.io/handoff-gate/demo/)
- [Six-slide carousel](https://sghatge.github.io/handoff-gate/carousel/)

## What it does

- Fail-closed decisions: missing evidence cannot silently pass.
- Deterministic policy checks; no LLM in the decision path.
- SHA-256 audit fingerprint over the evaluated package and policy version.
- Designed to support browser, Node.js, and CI workflows.

## Demo data and affiliation

All demo data is synthetic (fictional retailer “Lumen & Loom”). This is an independent project by Sangram Ghatge and is not affiliated with or endorsed by Adobe.

## GitHub Pages deployment

1. Upload the contents of this package to the repository root on branch `main`.
2. Open **Settings → Pages**.
3. Choose **Deploy from a branch**.
4. Select branch `main` and folder `/(root)`, then save.
5. Wait for the Pages deployment in **Actions** to complete.
6. Test the homepage, demo, and carousel in a private/incognito window.

Keep the existing MIT `LICENSE` file. This package includes the MIT license supplied with the project.
