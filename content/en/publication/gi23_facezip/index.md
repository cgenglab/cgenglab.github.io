---
title: "FaceZip: Automatic Texture Compression for Facial Blendshapes"
authors:
- yiyi_cai
- kinuwaki
- admin
date: "2023-05-25T00:00:00Z"
doi: ""

# Link authors to their profile page? (true/false)
link_authors: false

# Schedule page publish date (NOT publication's date).
publishDate: "2023-05-11T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *Graphics Interface 2023*
publication_short: In *GI 2023*

abstract: Recently, numerous cinematic and interactive entertainment production companies have adopted advanced capture systems to acquire faithful facial geometries and corresponding textures. However, it is difficult to animate these models in a controllable manner for real-time applications. Although blendshape is typically used for parameterizing facial geometries, dynamically changing the texture of the geometry is challenging. Because texture data are significantly larger than the vertex coordinates of the meshes, storing the texture of all the blendshape meshes is impractical. We present a method to compress texture data in a manner compatible with blendshape for real-time applications such as video games. Our method takes advantage of the locality of facial texture differences by blending a few textures with spatially different weights. Our method achieved a more accurate reconstruction of the original textures compared with the baseline principal component analysis. 

# Summary. An optional shortened abstract.
summary: Proceedings of Graphics Interface 2023

tags:
- Interactive Modeling
- Digital Human
- Character Animation
- Data-driven Animation
featured: false

links:
- name: OpenReview
  url: https://openreview.net/forum?id=AUa_CiMnZ9
- name: Presentation Video
  url: https://www.youtube.com/watch?v=-cxEloddXKs
url_pdf: https://www.dropbox.com/s/c0qgpn8sehwsyvt/2023_gi_facezip.pdf?dl=0

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

