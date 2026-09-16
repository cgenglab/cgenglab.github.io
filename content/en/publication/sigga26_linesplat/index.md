---
title: "Inverse Rendering for Modeling with Line Primitives"
authors:
- kenji-tojo
- Ariel Shamir
- admin  
- Bernd Bickel


date: "2026-09-15T00:00:03Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-09-15T00:00:03Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of Siggraph Asia 2026
publication_short: Siggraph Asia 2026

abstract:
  "Faithfully capturing diverse real-world objects with fuzzy, anisotropic structures—such as hair, fur, fibers, and textiles—for efficient real-time visualization remains challenging. Recent radiance field reconstruction methods capture these structures from multi-view images using translucent volumetric primitives such as 3D Gaussians rather than opaque low-dimensional primitives (e.g., triangles, line segments, and polylines), thereby limiting compatibility with standard depth-tested rasterization, reflection modeling, and physical simulation. We present an inverse rendering method for reconstructing fuzzy geometry using explicit line segments, which are rasterized on a subpixel grid for anti-aliasing to reproduce a semi-transparent appearance. While straightforward to render, optimizing numerous line primitives to match target images poses a significant challenge. We address this by introducing a stochastic differentiable rasterizer for line segments that produces informative gradients with respect to vertex positions, attributes, and discrete connectivity. Experiments on synthetic and real-world datasets show that our method outperforms surface-based approaches in capturing fuzzy boundaries and achieves quality comparable to volumetric representations while relying entirely on explicit geometry. The resulting representation integrates seamlessly with standard graphics pipelines, enabling cross-platform rendering, various shading models, and physical simulation."

# Summary. An optional shortened abstract.
summary: Proceedings of Siggraph Asia 2026

tags:
- 3D Reconstruction
featured: false

links:
- name: Project Page
  url: https://kenji-tojo.github.io/sa26-line-primitives/




#youtubeid: xoogpie7Nxs

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


