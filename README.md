# Hanji (Zhiheng) Xu — Resume

**[Download the PDF](Hanji-Xu-Resume.pdf)** · Portfolio: [design.hanjixu.com](https://design.hanjixu.com) · hxu01@risd.edu

Industrial designer and engineer. MID candidate at RISD (May 2027); B.A. Cognitive Science, UC Berkeley. Mechanisms, materials and objects that
report their own condition. Two patents; work shown most recently in *reharvest repair* (Providence Public Library, Oct–Dec 2026).

## About this repository
`resume.tex` is the LaTeX source, the same file compiled on Overleaf. It uses the `tagging` package: one source holds several
variants (industrial design, research, UX, data, environment). The active variant is chosen near `%--- Active Tag Selection ---`.

The source is generated from a YAML catalog of CV entries; edits happen there, not here. Every push of `resume.tex` rebuilds
`Hanji-Xu-Resume.pdf` through GitHub Actions.

Build locally:
```bash
tectonic resume.tex && mv resume.pdf Hanji-Xu-Resume.pdf
```

Template adapted from Shubham Mazumder's resume template (MIT). Content © Hanji Xu.
