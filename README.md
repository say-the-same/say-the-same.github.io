# Say the Same, Act Differently — project page

Project page for the NeurIPS 2026 paper *Say the Same, Act Differently: Diagnosing and Steering Text–Action Divergence in Reasoning VLAs*.

Plain static HTML with no build step. Math is rendered with KaTeX from a CDN.

## Local preview

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Deploy

Push to GitHub, then in **Settings → Pages** choose the `main` branch and the `/ (root)` folder.

## Before going public

- Fill in the Code link in `index.html` and remove its `is-soon` class.
- Update the BibTeX once the proceedings entry is final.

## Figures

Figures in `static/images/` are exported from the paper's `figure/` folder:
`TNAS_demo.pdf` → `tnas_demo.jpg`, `probe_finite_steps.pdf` → `probe_finite_steps.png`, `patch_demo_{1,2}.png` → `patch_demo_{1,2}.jpg`.
