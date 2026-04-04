---
title: "Fabricable 3D Wire Art"

authors:
- kenji-tojo
- Ariel Shamir
- Bernd Bickel
- admin

date: "2024-05-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of SIGGRAPH 2024
publication_short: SIGGRAPH 2024

abstract:
  "This paper presents a computational method for automatically creating fabricable 3D wire sculptures from various input modalities, including 3D models, images, and even text. There are several challenges to wire art creation. For example, artists must express the desired visual as a sparse wire representation. It is also difficult to manually bend wires in the air without guidance to fabricate the designed 3D curves. Our workflow solves these challenges by using two core techniques. First, we present an algorithm that automatically generates a fabricable 3D curve representation of the target based on a loss function that measures the semantic distance between the rendered curve and the target. The loss function can be defined using different pre-trained vision-language neural networks to generate wire art from different input types. The loss function is then optimized using differentiable rendering specifically targeting 3D parametric curves. Our method can incorporate various fabrication constraints on the wire as additional regularization terms in the optimization process. Second, we present an algorithm to generate a 3D printable jig structure that can be used to fabricate the generated wire path. The major challenge in the jig generation stems from the design of an intersection-free surface mesh for 3D printing, which we address with our inflation algorithm. The experimental results indicate that our method can handle a wider range of input types and can produce physically fabricable wire shapes compared to previous wire generation methods. Various wire arts have been fabricated using our 3D-printed jig to demonstrate its effectiveness in 3D wire bending."


# Summary. An optional shortened abstract.
summary: Proceedings of SIGGRAPH 2024

tags:
- Computational Fabrication
- Geometry Processing
- Rendering
featured: false

links:
- name: Project Page
  url: https://kenji-tojo.github.io/publications/fab3dwire/

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


