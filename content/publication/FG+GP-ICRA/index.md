---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Inference over Heterogeneous Finite-/Infinite-Dimensional Systems Using Factor Graphs and Gaussian Processes"
authors: ["David M. Rosen", "Guoquan Huang", "John. J. Leonard"]
date: 2014-06-01
doi: "10.1109/ICRA.2014.6907015"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-08T22:54:41-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Conference on Robotics and Automation"
publication_short: "ICRA"

abstract: "The ability to reason over partially observable networks of interacting states is a fundamental competency in probabilistic robotics. While the well-known factor graph and
Gaussian process models provide flexible and computationally efficient solutions for this inference problem in the special cases in which all of the hidden states are either finite-dimensional
parameters or real-valued functions, respectively, in many cases we are interested in reasoning about heterogeneous networks whose hidden states are comprised of both finite-dimensional
parameters *and* functions. To that end, in this paper we propose a novel probabilistic generative model that incorporates both factor graphs and Gaussian processes to model these heterogeneous
systems. Our model improves upon prior approaches to inference within these networks by removing the assumption of any specific set of conditional independences amongst the modeled states,
thereby significantly expanding the class of systems that can be represented. Furthermore, we show that inference within this model can always be performed by means of a two-stage
procedure involving inference within a factor graph followed by inference over a Gaussian process; by exploiting fast inference methods for the individual factor graph and Gaussian process
models to solve each of these subproblems in succession, we thus obtain a general framework for computationally efficient inference over heterogeneous finite-/infinite-dimensional systems.
"

# Summary. An optional shortened abstract.
summary: ""

tags: ["SLAM", "Factor graphs", "Gaussian process"]
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
#   E.g. `internal-project` references `content/project/internal-project/index.md`.#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
