---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Shonan Rotation Averaging: Global Optimality by Surfing $SO(p)^n$'
authors: ["Frank Dellaert*", "David M. Rosen*", "Jing Wu", "Robert Mahony", "Luca Carlone"]
date: 2020-08-23
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-08T16:13:12-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*European Conference on Computer Vision*"
publication_short: "ECCV"

abstract: 'Shonan Rotation Averaging is a fast, simple, and elegant rotation averaging algorithm that is guaranteed to recover globally optimal solutions under mild assumptions on the measurement noise. Our method employs semidefinite relaxation  to recover provably globally optimal solutions of the rotation averaging problem. In contrast to prior work, we show how to solve large-scale instances of these relaxations using manifold optimization on (only slightly) higher-dimensional rotation manifolds, re-using existing high-performance (but local) structure-from-motion pipelines. Our method thus preserves the speed and scalability of current SFM methods, while recovering globally optimal solutions. <p><span style="color:red">Spotlight talk (top 5%)</span></p>'

# Summary. An optional shortened abstract.
summary: 'A fast algorithm for *certifiably globally optimal* rotation averaging  </br><span style="color:red">ECCV spotlight talk (top 5%)</span>'

tags: ["Shonan averaging", "certifiably correct rotation averaging", "global optimization", "Riemannian optimization", "semidefinite programming", "convex relaxation"]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://arxiv.org/abs/2008.02737"
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
