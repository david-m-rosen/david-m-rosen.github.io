---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "An Incremental Trust-Region Method for Robust Online Sparse Least-Squares Estimation"
authors: ["David M. Rosen", "Michael Kaess", "John J. Leonard"]
date: 2012-05-14
doi: "10.1109/ICRA.2012.6224646"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-08T23:18:55-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Conference on Robotics and Automation"
publication_short: "ICRA"

abstract: "Many online inference problems in computer vision and robotics are characterized by probability distributions whose factor graph representations are sparse and whose factors are
all Gaussian functions of error residuals. Under these conditions, maximum likelihood estimation corresponds to solving a sequence of sparse least-squares minimization problems in which
additional summands are added to the objective function over time. In this paper we present Robust Incremental least-Squares Estimation (RISE), an incrementalized version of the Powell’s
Dog-Leg trust-region method suitable for use in online sparse least-squares minimization. As a trust-region method, Powell’s Dog-Leg enjoys excellent global convergence properties, and
is known to be considerably faster than both Gauss-Newton and Levenberg-Marquardt when applied to sparse least-squares problems. Consequently, RISE maintains the speed of current
state-of-the-art incremental sparse least-squares methods while providing superior robustness to objective function nonlinearities.
"

# Summary. An optional shortened abstract.
summary: ""

tags: ["SLAM", "computer vision", "online estimation", "nonlinear least-squares", "incremental optimization", "factor graphs"]
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
url_code: "http://people.csail.mit.edu/kaess/isam/"
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
