# ResponsibleRobotBench

Project website for **Benchmarking Risk-Aware Task-Level Decision Making for Robotic Manipulation with Large Multimodal Models**.

[Website](https://responsible-robot-benchmark.github.io/) · [Code](https://github.com/responsible-robot-benchmark/ResponsibleRobotBench) · [Paper and appendix](https://responsible-robot-benchmark.github.io/downloads/manuscript.pdf)

Lei Zhang, Ju Dong, Kaixin Bai, Minheng Ni, Yu Fu, Zoltán-Csaba Márton, Zhaopeng Chen, and Jianwei Zhang.

The website presents the 23-task benchmark, research findings, 23 simulation clips, and Franka and UR5e demonstrations. All figures, videos, fonts, and PDFs are included locally.

## Local preview

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`. No package installation or build step is required.

## Editing and publishing

- Edit the page content in `index.html`. Its CSS and JavaScript are bundled inline; `style.css` and `site.js` retain the matching source copies. Keep those copies consistent when changing styles or interactions.
- Store images and videos under `assets/`, and published PDFs under `downloads/`.
- `downloads/manuscript.pdf` is the full paper with the complete appendix. The page uses one combined paper-and-appendix download.
- Keep the author order and affiliations consistent with the paper. The citation is available in `citation.bib` and on the page.
- Push changes to `main`. GitHub Pages publishes the repository root; `.nojekyll` keeps this static site unchanged during deployment.

This repository contains the public project website. Benchmark implementation and usage instructions are maintained in the [code repository](https://github.com/responsible-robot-benchmark/ResponsibleRobotBench).
