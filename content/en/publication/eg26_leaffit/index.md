---
title: "LeafFit: Plant Assets Creation from 3D Gaussian Splatting"
authors:
- chang_luo
- admin

date: "2026-02-14T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-02-14T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Computer Graphics Forum (Proceedings of Eurographics 2026)
publication_short: CGF jounrnal (EG 2026)

abstract:
  "We propose LeafFit, a pipeline that converts 3D Gaussian Splatting (3DGS) of individual plants into editable, instanced mesh assets. While 3DGS faithfully captures complex foliage, its high memory footprint and lack of mesh topology make it incompatible with traditional game production workflows.

We address this by leveraging the repetition of leaf shapes; our method segments leaves from the unstructured 3DGS, with optional user interaction included as a fallback. A representative leaf group is selected and converted into a thin, sharp mesh to serve as a template; this template is then fitted to all other leaves via differentiable Moving Least Squares (MLS) deformation. At runtime, the deformation is evaluated efficiently on-the-fly using a vertex shader to minimize storage requirements.

Experiments demonstrate that LeafFit achieves higher segmentation quality and deformation accuracy than recent baselines while significantly reducing data size and enabling parameter-level editing."

# Summary. An optional shortened abstract.
summary: Computer Graphics Forum (Eurographics 2026)

tags:
- Gaussian Splatting
- Interactive Modeling
- 3D Reconstruction
featured: false

links:
- name: Project Page
  url: https://netbeifeng.github.io/LeafFit/


youtubeid: 7l-g5TWmFyU

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


