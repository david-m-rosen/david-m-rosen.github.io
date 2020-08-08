---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "RISE: An Incremental Trust-Region Method for Robust Online Sparse Least-Squares Estimation"
authors: ["David M. Rosen", "Michael Kaess", "John J. Leonard"]
date: 2014-10-01
doi: "https://doi.org/10.1109/TRO.2014.2321852"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-08T17:29:04-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Robotics"
publication_short: "T-RO"

abstract: "Many point estimation problems in robotics, computer vision and machine learning are formulated as instances
of the general problem of minimizing a sparse nonlinear sum-of-squares objective function. For inference problems of this type,
each input datum gives rise to a summand in the objective, and therefore performing *online* inference corresponds
to solving a *sequence* of sparse nonlinear least-squares problems in which additional summands are added to the
objective over time. In this paper we present *Robust Incremental least-Squares Estimation* (RISE), an incrementalized
version of the Powell’s Dog-Leg numerical optimization method suitable for use in online sequential sparse least-squares minimization. As a trust-region method, RISE is naturally robust
to nonlinearity and numerical ill-conditioning, and is provably globally convergent for a broad class of loss functions (twice-continuously differentiable functions with bounded sublevel sets). Consequently, RISE maintains the speed of current state-of-the-art online sparse least-squares methods while providing superior reliability.
"

# Summary. An optional shortened abstract.
summary: ""

tags: ["SLAM", "Computer vision", "online estimation", "Nonlinear least-squares", "incremental optimization"]
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
url_code:  "http://borg.cc.gatech.edu/sites/edu.borg/html/a00133.html"
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
