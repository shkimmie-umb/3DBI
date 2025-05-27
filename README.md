# Data and Materials for the Paper: "Benchmarking 3D Biomedical Imaging Readiness across Modern Medical Vision Systems"

This repository contains the data, evaluation scores, and supplementary materials used in our review and benchmarking of modern 3D biomedical imaging approaches, particularly focusing on their clinical relevance, 3D method sophistication, ML integration, and openness.

## Overview

This project introduces the **3D Biomedical Imaging Readiness Score (3DBI-RS)**, a unified scoring framework ranging from 0–8 points, composed of four subcategories:

- **Clinical Impact (0–2)**
- **3D Method (0–2)**
- **ML Integration (0–2)**
- **Openness (0–2)**

These scores help standardize and compare the translational readiness of various 3D imaging techniques across papers.

## Repository Structure

- `/data/table_papers.xlsx` — Score matrix and summary of all evaluated papers
- `/data/webgl_trends.xlsx` — Trends and metadata of 3D rendering/visualization techniques
- `/scripts/` — Scripts used for score aggregation and LaTeX table generation
- `/latex/` — LaTeX fragments used in the final paper draft
- `/figures/` — Exportable figures (PNG, PDF) including radar plots and score distributions
- `/notebooks/` — Jupyter notebooks for interactive data exploration

## Citation

If you use any part of this dataset or scoring system, please cite:

@misc{your_lastname2025readiness,
title={Benchmarking 3D Biomedical Imaging Readiness across Modern Medical Vision Systems},
author={Your Name and Collaborators},
year={2025},
note={Unpublished Manuscript},
url={https://shkimmie-umb.github.io/}
}

## License

This repository is licensed under the MIT License. See `LICENSE` for details.

---

For more context and examples, see [https://shkimmie-umb.github.io/](https://shkimmie-umb.github.io/) and our 3D scanning survey datasets.