---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Towards Lifelong Feature-Based Mapping in Semi-Static Environments"
authors: ["David M. Rosen", "Julian Mason", "John J. Leonard"]
date: 2016-05-16
doi: "10.1109/ICRA.2016.7487237"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-08T18:12:48-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Conference on Robotics and Automation"
publication_short: "ICRA"

abstract: 'The feature-based graphical approach to robotic
mapping provides a representationally rich and computationally
efficient framework for an autonomous agent to learn a model
of its environment. However, this formulation does not naturally
support *long-term* autonomy because it lacks a notion of environmental change.  In reality, "everything changes and nothing
stands still,” and any mapping and localization system that aims to support truly persistent autonomy must be similarly adaptive.
To that end, in this paper we propose a novel feature-based model of environmental evolution over time. Our approach is based upon the development of an expressive probabilistic generative
*feature persistence model* that describes the survival of abstract semi-static environmental features over time. We show that this model admits a recursive Bayesian estimator, the *persistence
filter*, that provides an exact online method for computing, at each moment in time, an explicit Bayesian belief over the persistence of each feature in the environment. By incorporating
this feature persistence estimation into current state-of-the-art graphical mapping techniques, we obtain a flexible, computationally efficient, and information-theoretically rigorous framework
for *lifelong* environmental modeling in an ever-changing world.'

# Summary. An optional shortened abstract.
summary: ""

tags: ["Semi-static SLAM", "Feature persistence", "Persistence filter"]
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
url_code:   "https://github.com/david-m-rosen/persistence_filter"
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
