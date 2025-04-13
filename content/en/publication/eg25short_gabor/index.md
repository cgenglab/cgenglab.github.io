---
title: "3D Gabor Splatting: Reconstruction of High-frequency Surface Texture using Gabor Noise"
authors:
- haato_watanabe
- kenji-tojo
- admin
date: "2025-04-05T00:00:00Z"
doi: ""

# Link authors to their profile page? (true/false)
link_authors: false

# Schedule page publish date (NOT publication's date).
publishDate: "2025-04-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Eurographics 2025 Short Paper Program
publication_short: EG 2025 short

abstract: 3D Gaussian splatting has experienced explosive popularity in the past few years in the field of novel view synthesis. The lightweight and differentiable representation of the radiance field using the Gaussian enables rapid and high-quality reconstruction and fast rendering. However, reconstructing objects with high-frequency surface textures (e.g., fine stripes) requires many skinny Gaussian kernels because each Gaussian represents only one color if viewed from one direction. Thus, reconstructing the stripes pattern, for example, requires Gaussians for at least the number of stripes. We present 3D Gabor splatting, which augments the Gaussian kernel to represent spatially high-frequency signals using Gabor noise. The Gabor kernel is a combination of a Gaussian term and spatially fluctuating wave functions, making it suitable for representing spatial high-frequency texture. We demonstrate that our 3D Gabor splatting can reconstruct various high-frequency textures on the objects.

# Summary. An optional shortened abstract.
summary: Eurographics 2025 Short Paper Program

tags:
- Gaussian Splatting
- 3D Reconstruction
featured: false

links:
- name: Project Page
  url: https://haato-w.github.io/3d-gabor-splatting-project-page/


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

