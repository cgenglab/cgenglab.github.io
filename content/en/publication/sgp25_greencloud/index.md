---
title: "GreenCloud: Volumetric Gradient Filtering via Regularized Green’s Functions"
authors:
- kenji-tojo
- admin
date: "2025-06-01T00:00:00Z"
doi: ""

# Link authors to their profile page? (true/false)
link_authors: false

# Schedule page publish date (NOT publication's date).
publishDate: "2025-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of Symposium on Geometry Processing 2025
publication_short: SGP 2025

abstract: Gradient-based optimization is a fundamental tool in geometry processing, but it is often hampered by geometric distortion arising from noisy or sparse gradients. Existing methods mitigate these issues by filtering (i.e., diffusing) gradients over a surface mesh, but they require explicit mesh connectivity and solving large linear systems. In this work, we introduce a gradient filtering method tailored for point-based geometry, which bypasses explicit connectivity using regularized Green’s functions to directly compute the filtered gradient field from discrete spatial points. Additionally, our approach incorporates elastic deformation based on Green’s function of linear elasticity (known as Kelvinlets), reproducing various elastic behaviors such as smoothness and volume preservation while improving robustness in affine transformations. We further accelerate computation using a hierarchical Barnes–Hut style approximation, enabling scalable optimization of one million points. Our method significantly improves convergence across diverse applications, including reconstruction, editing, stylization, and simplified optimization experiments with Gaussian splatting.

# Summary. An optional shortened abstract.
summary: Proceedings of Symposium on Geometry Processing 2025 , <font color=red>Honorable Mention Award</font>

tags:
- Gaussian Splatting
- Inverse Rendering
- 3D Reconstruction
- Gradient Filtering
featured: false

links:
- name: Project Page
  url: https://kenji-tojo.github.io/publications/greencloud/


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

