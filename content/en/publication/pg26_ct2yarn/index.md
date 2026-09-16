---
title: "CT2Yarn: Yarn-Level Reconstruction of Crochet from Computed Tomography
"
authors:
- chang_luo
- admin

date: "2026-09-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-09-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of Pacific Graphics 2026
publication_short: PG 2026

abstract:
  "We introduce CT2Yarn, a human-in-the-loop framework for recovering a single continuous yarn path from micro-computed tomography (micro-CT) scans of real crochet objects. Crochet is a craft that creates complex three-dimensional shapes by interlocking loops formed from a single yarn. Recovering the underlying yarn path from external observations is challenging because of severe self-occlusion. While micro-CT reveals the full internal structure of a crochet object, the volumetric scan alone does not explicitly encode how the yarn traverses the object. This challenge stems from the hierarchical structure of yarn: a yarn consists of multiple twisted plies, and each ply itself consists of twisted fibers. Consequently, local fiber orientations observed in micro-CT scans are not aligned with the overall yarn direction. To recover yarn-level orientations from ply-level fiber orientations, we first estimate local fiber directions using Gabor filtering and convert the volume into an oriented point cloud. We then introduce an anisotropic mean-shift procedure that aggregates local fiber orientations within a neighborhood of the yarn radius into yarn-level orientation estimates. Combined with an automatic topology skeletonization strategy, our method extracts yarn-path fragments. Subsequent fragment linking, junction cleaning, and loop detection merge these trees into a small number of long curves. Where the automatic reconstruction remains ambiguous, a sketch-based user interface enables users to interactively complete the single continuous yarn path. The recovered yarn path enables downstream applications including physically based simulation, ply-level rendering, and stitch-pattern extraction."

# Summary. An optional shortened abstract.
summary: Proceedings of PG 2026

tags:
- 3D Reconstruction
- Volume Data
featured: false

links:
url_pdf: https://arxiv.org/abs/2609.06950



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


