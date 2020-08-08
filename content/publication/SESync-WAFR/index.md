---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Certifiably Correct Algorithm for Synchronization over the Special Euclidean Group"
authors: ["David M. Rosen", "Luca Carlone", "Afonso S. Bandeira", "John J. Leonard"]
date: 2016-12-18
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-08T11:26:42-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*International Workshop on the Algorithmic Foundations of Robotics*"
publication_short: "WAFR"

abstract: "Many important geometric perception tasks require *synchronization over the special Euclidean group*: estimate a set of unknown *poses* (positions and orientations in 2D or 3D space) from a collection of noisy relative measurements between them.  For example, the foundational problems of pose-graph SLAM (in robotics), bundle adjustment (in computer vision), and sensor network localization (in distributed sensing) all belong to this class.  This estimation problem is both *high-dimensional* (due to the large number of poses that typically must be estimated) and *nonconvex* (due to the nonconvexity of the space of orientations itself), and therefore computationally hard to solve in general.  In practice, this  manifests in the form of *many* significantly suboptimal local minima that can entrap the local optimization methods commonly applied to this problem. "

# Summary. An optional shortened abstract.
summary: "Find *provably globally optimal* solutions of pose-graph SLAM"

tags: ["SE-Sync", "Certifiably correct SLAM", "Pose-graph SLAM", "Global optimization", "Riemannian optimization", "Semidefinite programming", "Convex relaxation"]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code: "https://github.com/david-m-rosen/SE-Sync"
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
  focal_point: "Left"
  preview_only: true

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
