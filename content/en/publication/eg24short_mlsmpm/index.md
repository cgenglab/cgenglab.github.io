---
title: "Accurate Boundary Condition for Moving Least Squares Material Point Method using Augmented Grid Points"
authors:
- Riku Toyota
- admin
date: "2024-03-20T00:00:00Z"
doi: ""

# Link authors to their profile page? (true/false)
link_authors: false

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: Eurographics 2024 Short Paper Program
publication_short: EG 2024 short

abstract: This paper introduces an accurate boundary-handling method for the moving least squares (MLS) material point method (MPM), which is a popular scheme for robustly simulating deformable objects and fluids using a hybrid of particle and grid representations coupled via MLS interpolation. Despite its versatility with different materials, traditional MPM suffers from undesirable artifacts around wall boundaries, for example, particles pass through the walls and accumulate. To address these issues, we present a technique inspired by a line handler for MLS-based image manipulation. Specifically, we augment the grid by adding points along the wall boundary to numerically compute the integration of the MLS weight. These additional points act as background grid points, improving the accuracy of the MLS interpolation around the boundary, albeit with a marginal increase in computational cost. In particular, our technique makes the velocity perpendicular to the wall nearly zero, preventing particles from passing through the wall. We compare the boundary behavior of 2D simulation against that of naive approach.

# Summary. An optional shortened abstract.
summary: Eurographics 2024 Short Paper Program

tags:
- Fluid Dynamics
- Physics Simulation
featured: false

links:
- name: Supplemental Video
  url: https://www.youtube.com/watch?v=Rcp94v6mU3w
- name: Presentation Video
  url: https://www.youtube.com/watch?v=jtrwOCZX7ss  
- name: GitHub
  url: https://github.com/nobuyuki83/accurate_bc_for_mls_mpm

url_pdf: https://www.dropbox.com/scl/fi/3ldjvx7ilitsk9haeoy7p/2024_egshort_mlsmpm.pdf?rlkey=4oofpry4tdvkhl2zxpyy64h0l&dl=0

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

