---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'A Smooth Representation of Belief over $SO(3)$ for Deep Rotation Learning with Uncertainty'
authors: ["Valentin Peretroukhin", "Matthew Giamou", "David M. Rosen", "W. Nicholas Greene", "Nicholas Roy", "Jonathan Kelly"]
date: 2020-07-12
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-08T16:56:06-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Robotics: Science and Systems"
publication_short: "RSS"

abstract: 'Accurate rotation estimation is at the heart of robot perception tasks such as visual odometry and object pose estimation. Deep neural networks have provided a new way to perform these tasks, and the choice of rotation representation is an important part of network design. In this work, we present a novel symmetric matrix representation of the 3D rotation group, SO(3), with two important properties that make it particularly suitable for learned models: (1) it satisfies a smoothness property that improves convergence and generalization when regressing large rotation targets, and (2) it encodes a symmetric Bingham belief over the space of unit quaternions, permitting the training of uncertainty-aware models. We empirically validate the benefits of our formulation by training deep neural rotation regressors on two data modalities. First, we use synthetic point-cloud data to show that our representation leads to superior predictive accuracy over existing representations for arbitrary rotation targets. Second, we use image data collected onboard ground and aerial vehicles to demonstrate that our representation is amenable to an effective out-of-distribution (OOD) rejection technique that significantly improves the robustness of rotation estimates to unseen environmental effects and corrupted input images, without requiring the use of an explicit likelihood loss, stochastic sampling, or an auxiliary classifier. This capability is key for safety-critical applications where detecting novel inputs can prevent catastrophic failure of learned models.
<p><span style="color:red">Best Student Paper Award</span></p>'

# Summary. An optional shortened abstract.
summary: 'A novel parameterization for deep Bayesian rotation estimation  </br><span style="color:red">Best Student Paper Award (RSS 2020)</span>'

tags: ["deep learning", "Bayesian estimation", "rotation estimation"]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "http://www.roboticsproceedings.org/rss16/p007.pdf"
url_code: "https://github.com/utiasSTARS/bingham-rotation-learning"
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: "https://www.youtube.com/watch?v=iEp6amPkkKw#action=share"

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
