---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Computational Enhancements for Certifiably Correct SLAM"
authors: ["David M. Rosen", "Luca Carlone"]
date: 2017-09-24
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-09T00:31:06-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Workshop paper
publication_types: ["9"]

# Publication name and optional abbreviated publication name.
publication: 'International Conference on Intelligent Robots and Systems workshop "Introspective Methods for Reliable Autonomy'
publication_short: "IROS workshops"

abstract: "We investigate numerical and computational aspects of the use of convex relaxation for simultaneous localization and mapping (SLAM). Recent work has shown that convex relaxation provides an effective tool for computing, and certifying the correctness of, *globally optimal* SLAM solutions. This paper expands upon this prior work by demonstrating how to exploit the structure of the relaxed optimization problem to design very fast solvers, capable of computing globally optimal trajectories with thousands of poses in a fraction of a second. In particular, we describe several computational enhancements for accelerating the underlying Riemannian trust-region optimization method, including the use of structure-exploiting matrix decomposition, iterative linear-algebraic techniques, truncated-Newton methods, and preconditioning strategies. We also describe methods for accelerating the minimum-eigenvalue computation used to certify the optimality of a recovered estimate. We have incorporated
these computational enhancements in an updated version of the SE-Sync library, and released the corresponding code online. Experimental results indicate that this enhanced implementation of SE-Sync is approximately twice as fast as GTSAM, a highly optimized, state-of-the-art library for SLAM."

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
