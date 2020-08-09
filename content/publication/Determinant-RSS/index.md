---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "On the Inclusion of Determinant Constraints in Lagrangian Duality for 3D SLAM"
authors: ["Roberto Tron", "David M. Rosen", "Luca Carlone"]
date: 2015-07-15
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-09T00:13:30-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Workshop
publication_types: ["9"]

# Publication name and optional abbreviated publication name.
publication: 'Robotics: Science and Systems workshop "The Problem of Mobile Sensors"'
publication_short: "RSS workshops"

abstract: "Recent work in 3D Pose Graph Optimization (PGO) shows how a dual Lagrangian formulation of the problem can be used to verify (and possibly certify) the quality of a
given solution. A limitation of current approaches is that they relax the positive determinant constraint for the rotations: in consequence, if they fail to certify an optimal solution (i.e., if the duality gap is nonzero), one cannot determine if this is due to the relaxation itself, or if it is an intrinsic feature of the problem at hand. In this paper we show how one can include the determinant constraints in the derivation of the dual, thus showing that their relaxation is unnecessary. We show experimentally that this complete formulation does not lead to tangible differences with respect to the original, relaxed version. This indicates that the reasons for failure in providing a certificate of optimality are intrinsic to the problem, and that the determinant constraints are somehow redundant in common PGO instances."

# Summary. An optional shortened abstract.
summary: ""

tags: ["verification", "pose-graph SLAM", "Lagrangian duality", "global optimality"]
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
