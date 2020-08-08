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

abstract: 'Many important geometric perception tasks require *synchronization over the special Euclidean group*: estimate a set of unknown *poses* (positions and orientations in 2D or 3D space) from a collection of noisy relative measurements between them.  Examples of this class include the foundational problems of pose-graph SLAM (in robotics), camera motion estimation (in computer vision), and sensor network localization (in distributed sensing), among others.  This inference problem is typically formulated as a nonconvex maximum likelihood estimation that
is computationally hard to solve in general. In practice, this hardness manifests in the form of *many* significantly suboptimal local minima that can entrap standard local optimization methods.  To address this pitfall, in this work we propose a new approach to special Euclidean synchronization based upon *convex relaxation* rather than local search.  Specifically, we derive a (convex) semidefinite relaxation of the maximum likelihood estimation whose minimizer provides an ***exact***, ***globally optimal*** estimator so long as the noise on the available measurements is not too large; furthermore, whenever this holds, it is possible to *verify* this fact *a posteriori*, thereby *certifying* the optimality of the recovered estimate. In practice, our algorithm (**SE-Sync**) is capable of recovering certifiably globally optimal solutions when the available measurements are corrupted by noise up to an order of magnitude greater than that typically encountered in robotics and computer vision applications, and does so more than an order of magnitude faster than the Gauss-Newton-based approach that forms the basis of current state-of-the-art techniques.

<p><span style="color:red">Best Paper Award</span></p>'

# Summary. An optional shortened abstract.
summary: 'Find *provably globally optimal* solutions of pose-graph SLAM  </br><span style="color:red">Best Paper Award (WAFR 2016)</span>'

tags: ["SE-Sync", "Certifiably correct SLAM",  "Pose-graph SLAM", "Global optimization", "Riemannian optimization", "Semidefinite programming", "Convex relaxation"]
#tags: []
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
  focal_point: "Smart"
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
