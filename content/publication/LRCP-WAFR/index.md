---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Scalable Low-Rank Semidefinite Programming for Certifiably Correct Machine Perception"
authors: ["David M. Rosen"]
date: 2020-06-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-08T17:59:24-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "International Workshop on the Algorithmic Foundations of Robotics"
publication_short: ""

abstract: " Semidefinite relaxation has recently emerged as a powerful
technique for machine perception, in many cases enabling the recovery of *certifiably globally optimal* solutions of generally-intractable nonconvex estimation problems. However, the high computational cost of standard interior-point methods for semidefinite optimization prevents these algorithms from scaling effectively to the high-dimensional problems frequently encountered in machine perception tasks. To address this challenge, in this paper we present an efficient algorithm for solving the large-scale but *low-rank* semidefinite relaxations that underpin current
certifiably correct machine perception methods. Our algorithm preserves the scalability of current state-of-the-art low-rank semidefinite optimizers that are *custom-built* for the geometry of specific machine perception problems, but generalizes to a broad class of convex programs over spectrahedral sets *without* the need for detailed manual analysis or design.
The result is an easy-to-use, general-purpose computational tool capable of supporting the development and deployment of a broad class of novel certifiably correct machine perception methods.
"

# Summary. An optional shortened abstract.
summary: "Build your own certifiably correct machine perception methods"

tags: ["Certifiably correct perception", "Semidefinite programming", "Low-rank semidefinite programming", "Convex relaxation"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "http://robotics.cs.rutgers.edu/wafr2020/wp-content/uploads/sites/7/2020/05/WAFR_2020_FV_84.pdf"
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
