---
title: "Free-form Floor Plan Design using Differentiable Voronoi Diagram"
authors:
- xuanyu_wu
- kenji-tojo
- admin


date: "2024-08-18T00:00:00Z"
doi: ""

# Link authors to their profile page? (true/false)
link_authors: true

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of Pacific Graphics 2024
publication_short: PG 2024

abstract: Designing floor plans is difficult because various constraints must be satisfied by the layouts of the internal walls. This paper presents a novel shape representation and optimization method for designing floor plans based on the Voronoi diagrams. Our Voronoi diagram implicitly specifies the shape of the room using the distance from the Voronoi sites, thus facilitating the topological changes in the wall layout by moving these sites. Since the differentiation of the explicit wall representation is readily available, our method can incorporate various constraints, such as room areas and room connectivity, into the optimization. We demonstrate that our method can generate various floor plans while allowing users to interactively change the constraints. 


# Summary. An optional shortened abstract.
summary: Proceedings of Pacific Graphics 2024

tags:
- Geometry Processing
featured: false

links:
- name: Project Page
  url: https://github.com/nobuyuki83/floor_plan
url_pdf: https://www.dropbox.com/scl/fi/culi7j1v14r9ax98rfmd6/2024_pg24_floorplan.pdf?rlkey=s5xwncuybrtsj5vyphhn61u0h&dl=0



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
