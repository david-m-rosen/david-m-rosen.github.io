---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "SE-Sync: A Certifiably Correct Algorithm for Synchronization over the Special Euclidean Group"
authors: ["David M. Rosen", "Luca Carlone", "Afonso S. Bandeira", "John J. Leonard"]
date: 2017-02-05
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-09T00:46:30-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["4"]

# Publication name and optional abbreviated publication name.
publication: "MIT Computer Science and Artificial Intelligence Laboratory Technical Report"
publication_short: "MIT CSAIL Technical Report"

abstract: "Many important geometric estimation problems naturally take the form of *synchronization over the special Euclidean group*: estimate the values of a set of unknown poses given noisy measurements of a subset of their pairwise relative transforms. Examples of this class include the foundational problems of pose-graph simultaneous localization and mapping (SLAM) (in robotics), camera motion estimation (in computer vision), and sensor network localization (in distributed sensing), among others. This inference problem is typically formulated as a nonconvex maximum-likelihood estimation that is computationally hard to solve in general. Nevertheless, in this paper we present an algorithm that is able to efficiently recover *certifiably globally optimal* solutions of the special Euclidean synchronization problem in a non-adversarial noise regime. The crux of our approach is the development of a semidefinite relaxation of the maximum-likelihood estimation whose minimizer provides an *exact* MLE so long as the magnitude of the noise corrupting the available measurements falls below a certain critical threshold; furthermore, whenever exactness obtains, it is possible to *verify* this fact *a posteriori*, thereby *certifying* the optimality of the recovered estimate. We develop a specialized optimization scheme for solving large-scale instances of this semidefinite relaxation by exploiting its low-rank, geometric, and graph-theoretic structure to reduce it to an equivalent optimization problem defined on a low-dimensional Riemannian manifold, and then design a Riemannian truncated-Newton trust-region method to solve this reduction efficiently. Finally, we combine this fast optimization approach with a simple rounding procedure to produce our algorithm, *SE-Sync*. Experimental evaluation on a variety of simulated and real-world pose-graph SLAM datasets shows that SE-Sync is capable of recovering certifiably globally optimal solutions when the available measurements are corrupted by noise up to an order of magnitude greater than that typically encountered in robotics and computer vision applications, and does so more than an order of magnitude faster than the Gauss-Newton-based approach that forms the basis of current state-of-the-art techniques."

# Summary. An optional shortened abstract.
summary: ""

tags: ["SE-Sync", "certifiably correct SLAM", "pose-graph SLAM", "global optimization", "Riemannian optimization", "semidefinite programming", "convex relaxation"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://dspace.mit.edu/bitstream/handle/1721.1/106885/MIT-CSAIL-TR-2017-002.pdf?sequence=1&isAllowed=y
url_code:  https://github.com/david-m-rosen/SE-Sync
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
