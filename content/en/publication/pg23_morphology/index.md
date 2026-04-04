---
title: "Fast Grayscale Morphology for Circular Window"
authors:
- moroto
- admin


date: "2023-09-21T00:00:00Z"
doi: ""

# Link authors to their profile page? (true/false)
link_authors: true

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: Computer Graphics Forum 42(7) (Proceedings of Pacific Graphics 2023)
publication_short: PG 2023

abstract: Morphological operations are among the most popular classic image filters. The filter assumes the maximum or minimum value within a window and is often used for light object thickening and thinning operations, which are important components of various workflows, such as object recognition and stylization. Circular windows are preferred over rectangular windows for obtaining isotropic filter results. However, the existing efficient algorithms focus on rectangular or binary input images. Efficient morphological operations with circular windows for grayscale images remain challenging. In this study, we present a fast grayscale morphology heuristic computation algorithm that decomposes circular windows using the convex hull of circles. We significantly accelerate traditional methods based on Minkowski addition by introducing new decomposition rules specialized for circular windows. As our morphological operation using a convex hull can be computed independently for each pixel, the algorithm is efficient for modern multithreaded hardware.


# Summary. An optional shortened abstract.
summary: Computer Graphics Forum 42(7) (Pacific Graphics 2023)

tags:
- Image Processing
featured: false

links:
url_pdf: https://www.dropbox.com/scl/fi/58yzb8b52g15e4ag19mb7/2023_pg23_morphology.pdf?rlkey=gaq7mglj14wivlsp27vggb9tz&dl=0



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
