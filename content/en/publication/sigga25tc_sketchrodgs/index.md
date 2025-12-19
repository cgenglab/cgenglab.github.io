---
title: "SketchRodGS: Sketch-based Extraction of Slender Geometries for Animating Gaussian Splatting Scenes"
authors:
- haato_watanabe
- admin
date: "2025-10-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-10-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ACM SIGGRAPH Asia 2025 Technical Communications
publication_short: SIGGA 2025 Tech. Com.

abstract: Physics simulation of slender elastic objects often requires discretization as a polyline. However, constructing a polyline from Gaussian splatting is challenging as Gaussian splatting lacks connectivity information and the configuration of Gaussian primitives contains much noise. This paper presents a method to extract a polyline representation of the slender part of the objects in a Gaussian splatting scene from the user’s sketching input. Our method robustly constructs a polyline mesh that represents the slender parts using the screen-space shortest path analysis that can be efficiently solved using dynamic programming. We demonstrate the effectiveness of our approach in several in-the-wild examples.

# Summary. An optional shortened abstract.
summary: ACM SIGGRAPH Asia 2025 Technical Communications, <font color=red>Best Communications Award</font>

tags:
- Gaussian Splatting
- Sketch-based Interface
- Interactive Modeling
- Physics simulation
featured: false

links:
- name: Project Page
  url: https://haato-w.github.io/sketch-rod-gs-project-page/


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

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

