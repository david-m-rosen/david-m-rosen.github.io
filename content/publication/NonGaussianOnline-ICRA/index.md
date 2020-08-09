---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Robust Incremental Online Inference over Sparse Factor Graphs: Beyond the Gaussian Case"
authors: ["David M. Rosen", "Michael Kaess", "John J. Leonard"]
date: 2013-05-06
doi: "10.1109/ICRA.2013.6630699"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-08T23:06:41-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Conference on Robotics and Automation"
publication_short: "ICRA"

abstract: "Many online inference problems in robotics and AI are characterized by probability distributions whose factor graph representations are sparse. While there do exist some computationally efficient algorithms (e.g. incremental smoothing and mapping (iSAM) or Robust Incremental least-Squares Estimation (RISE)) for performing online incremental maximum likelihood
estimation over these models, they generally require that the distribution of interest factors as a product of Gaussians, a rather restrictive assumption. In this paper, we investigate the
possibility of performing efficient incremental online estimation over sparse factor graphs in the non-Gaussian case. Our main result is a method that generalizes iSAM and RISE by removing the assumption of Gaussian factors, thereby significantly expanding the class of distributions to which these algorithms can be applied. The generalization is achieved by means of a simple algebraic reduction that under relatively mild conditions (boundedness of each of the factors in the distribution of interest) enables an instance of the general maximum likelihood estimation problem to be reduced to an equivalent instance of least-squares minimization that can be solved efficiently online by application of iSAM or RISE. Through this construction we obtain robust, computationally efficient, and *mathematically correct* incremental online maximum likelihood estimators for non-Gaussian distributions over sparse factor graphs."

# Summary. An optional shortened abstract.
summary: ""

tags: ["SLAM", "robust estimation", "non-Gaussian estimation", "factor graph"]
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
