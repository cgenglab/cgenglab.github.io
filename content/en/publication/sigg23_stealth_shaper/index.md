---
title: "Stealth Shaper: Reflectivity Optimization as Surface Stylization"
authors:
- kenji-tojo
- Ariel Shamir
- Bernd Bickel
- admin

date: "2023-05-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of SIGGRAPH 2023
publication_short: SIGGRAPH 2023

abstract:
  "We present a technique to optimize the reflectivity of a surface while preserving its overall shape. The naïve optimization of the mesh vertices using the gradients of reflectivity simulations results in undesirable distortion. In contrast, our robust formulation optimizes the surface normal as an independent variable that bridges the reflectivity term with differential rendering, and the regularization term with as-rigid-as-possible elastic energy. We further adaptively subdivide the input mesh to improve the convergence. Consequently, our method can minimize the retroreflectivity of a wide range of input shapes, resulting in sharply creased shapes ubiquitous among stealth aircraft and Sci-Fi vehicles. Furthermore, by changing the reward for the direction of the outgoing light directions, our method can be applied to other reflectivity design tasks, such as the optimization of architectural walls to concentrate light in a specific region. We have tested the proposed method using light-transport simulations and real-world 3D-printed objects."


# Summary. An optional shortened abstract.
summary: Proceedings of SIGGRAPH 2023

tags:
- Computational Fabrication
- Geometry Processing
- Rendering
featured: false

links:
- name: Project Page
  url: https://kenji-tojo.github.io/publications/stealthshaper/

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---


