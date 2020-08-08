---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Convex Relaxation for Approximate Global Optimization in Simultaneous Localization and Mapping"
authors: ["David M. Rosen", "Charles DuHadway", "John J. Leonard"]
date: 2015-05-25
doi: "10.1109/ICRA.2015.7140014"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-08T18:35:55-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Conference on Robotics and Automation"
publication_short: "ICRA"

abstract: "Modern approaches to simultaneous localization and mapping (SLAM) formulate the inference problem as a high-dimensional but sparse nonconvex M-estimation, and then apply
general first- or second-order smooth optimization methods to recover a local minimizer of the objective function. The performance of any such approach depends crucially upon initializing
the optimization algorithm near a good solution for the inference problem, a condition that is often difficult or impossible to guarantee in practice. To address this limitation, in this paper
we present a formulation of the SLAM M-estimation with the property that, by expanding the feasible set of the estimation program, we obtain a *convex relaxation* whose solution approximates
the globally optimal solution of the SLAM inference problem and can be recovered using a smooth optimization method initialized at *any* feasible point. Our formulation thus provides a means
to obtain a high-quality solution to the SLAM problem *without* requiring high-quality initialization."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Pose-graph SLAM", "Semidefinite relaxation", "Convex relaxation"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
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
