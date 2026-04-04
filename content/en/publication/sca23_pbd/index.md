---
title: "Two-Way Coupling of Skinning Transformations and Position Based Dynamics"
authors:
- yuhan_wu
- admin

date: "2023-06-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of the ACM in Computer Graphics and Interactive Techniques (PACMCGIT) journal (Proceedings of SCA 2023)
publication_short: PACMCGIT jounrnal (SCA 2023)

abstract:
  "Skinning transformations enable digital characters to be animated with minimal user input. Physics simulations can improve the detailed dynamic movement of an animated character; however, such details are typically added in the post-processing stage after the overall animation is specified. We propose a novel interactive framework that unifies skinning transformations and kinematic simulations using position-based dynamics (PBD). Our framework allows an arbitrarily skinned character to be partially manipulated by the user, and a kinematic physics solver automatically complements the behavior of the entire character. This is achieved by introducing new steps into the PBD algorithm: (i) lightweight optimization to identify the skinning transformations, which is similar to inverse kinematics, and (ii) a position-based constraint to restrict the PBD solver to the complementary subspace of the skinning deformation. Our method combines the best of the two methods: the controllability and shape preservation of the skinning transformation, and the efficiency, simplicity, and unconditional stability of the PBD solver. Our interface allows novices to create vibrant animations without tedious editing."

# Summary. An optional shortened abstract.
summary: PACMCGIT journal (SCA 2023)

tags:
- Physics Simulation
featured: false

links:
- name: Project Page
  url: https://yoharol.github.io/pages/control_pbd/



youtubeid: 6Sm_JwhTLKc

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


