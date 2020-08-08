---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Lagrangian Duality in 3D SLAM: Verification Techniques and Optimal Solutions"
authors: ["Luca Carlone", "David M. Rosen", "Giuseppe Calafiore", "John J. Leonard", "Frank Dellaert"]
date: 2015-09-25
doi: "10.1109/IROS.2015.7353364"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-08T18:48:28-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/RSJ International Conference on Intelligent Robots and Systems"
publication_short: "IROS"

abstract: "State-of-the-art techniques for simultaneous localization and mapping (SLAM) employ iterative nonlinear optimization methods to compute an estimate for robot poses. While these techniques often work well in practice, they do not provide guarantees on the quality of the estimate. This paper shows that *Lagrangian duality* is a powerful tool to assess the quality of a given candidate solution. Our contribution is threefold. First, we discuss a revised formulation of the SLAM inference problem. We show that this formulation is probabilistically grounded and has the advantage of leading to an optimization problem with quadratic objective. The second contribution is the derivation of the corresponding *Lagrangian dual* problem. The SLAM dual problem is a (convex) *semidefinite program*, which can be solved reliably and globally by off-the-shelf solvers. The third contribution is to discuss the relation between the original SLAM problem and its dual. We show that from the dual problem, one can evaluate the quality (i.e., the suboptimality gap) of a candidate SLAM solution, and ultimately provide a certificate of optimality. Moreover, when the duality gap is zero, one can compute a guaranteed optimal SLAM solution from the dual problem, circumventing non-convex optimization. We present extensive (real and simulated) experiments supporting our claims and discuss practical relevance and open problems."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Verification", "SLAM", "Lagrangian Duality", "Global optimality"]
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
