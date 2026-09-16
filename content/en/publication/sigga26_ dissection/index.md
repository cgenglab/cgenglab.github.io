---
title: "Voronoi Scissors: Approximate Dissection of 2D Shapes with Continuous Optimization"
authors:
- Anran Qi
- Nico Pietroni
- Mikhail Bessmeltsev
- admin
- Adrien Bousseau
- Takeo Igarashi

date: "2026-09-15T00:00:01Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-09-15T00:00:01Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of Siggraph Asia 2026
publication_short: Siggraph Asia 2026

abstract:
  " The dissection of planar shapes into a common set of reusable pieces is a classical problem, with connections to geometry processing, fabrication, and design. Despite its long-standing interest, the problem remains challenging due to the interplay of geometric constraints and combinatorial complexity. Existing approaches are limited to exact dissection of simple polygonal shapes, or can only handle a small number of pieces and introduce significant distortion when performing approximate dissection of more complex shapes.

We present a fully automatic method for dissecting two-dimensional shapes into a shared set of pieces that can be rearranged to approximate multiple target configurations. Our approach formulates the problem as a hybrid optimization pipeline. We first perform a continuous optimization based on a Voronoi-driven decomposition to generate an initial partition. This is followed by a global optimization step that determines a consistent rearrangement of pieces while enforcing structural constraints required for valid, rigid, and non-overlapping assemblies. The final refinement stage refines the solution to best approximate the input shapes.

Our method guarantees that all pieces admit rigid, non-overlapping rearrangements. Moreover, our pieces are more compact and yield less distortion than the ones obtained by prior work. We demonstrate the generality of our approach across novel dissection scenarios, including multi-shape rearrangements, shapes with complex topology, and reuse-driven settings where a fixed source shape is partitioned to approximate a target. "

# Summary. An optional shortened abstract.
summary: Proceedings of Siggraph Asia 2026

tags:
- Geometry Processing
- Computational Fabrication
featured: false

links:
- name: Project Page
  url: https://anranqi.github.io/VoronoiScissors/#top



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


