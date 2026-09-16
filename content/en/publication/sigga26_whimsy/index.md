---
title: "Generative Whimsy Jigsaws"
authors:
- Jeremy Chew
- kenji-tojo
- admin  
- Bernd Bickel


date: "2026-09-15T00:00:02Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-09-15T00:00:02Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of Siggraph Asia 2026
publication_short: Siggraph Asia 2026

abstract:
  "Unlike conventional jigsaw puzzles which partition an image into a predefined set of rectangular pieces, ``whimsy'' jigsaw puzzles depict a variety of objects, such as animals, vehicles, and characters, through the outlines of the pieces themselves. Although skilled artists have created visually compelling and playful puzzles within this framework, designing whimsy jigsaws remains highly challenging---creators must simultaneously partition a given outline into multiple interlocking pieces while ensuring that each piece conveys a recognizable visual concept. This difficulty limits accessibility, preventing casual creation by less experienced users, particularly when designing puzzles with many pieces and concepts. To address this challenge, we present a computational framework for automatically designing whimsy jigsaws from a loosely specified set of visual targets, each assigned to an individual piece. Specifically, we take a set of text prompts as input and use differentiable optimization to refine the geometry of each piece, guided by a pre-trained diffusion model. Since naive formulations suffer from a fundamental tension in whimsy jigsaws between geometric validity and recognizability, this paper develops a representation for planar partitioning that guarantees the partitioning of the domain into a specified number of connected pieces, while allowing for highly flexible geometric evolution. The key component is the scalar slowness field, which is used to compute a warped geodesic distance field given a point source by solving the Eikonal equation. Given distance fields from multiple sources, we can compute warped Voronoi cells that define pieces of a puzzle. The representation is fully differentiable, with gradients computed via adjoint sensitivity analysis, and the slowness field is represented as a neural implicit field. Experimental results demonstrate that our framework generates diverse, thematically consistent jigsaw puzzles across a wide range of user prompts, enabling the automated design of puzzles with complex, figurative pieces."

# Summary. An optional shortened abstract.
summary: Proceedings of Siggraph Asia 2026

tags:
- Geometry Processing
- Computational Fabrication
featured: false

links:
#- name: Project Page
#  url: https://kenji-tojo.github.io/sa26-line-primitives/




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


