---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "JA-POLS:  A Moving-Camera Background Model via Joint Alignment and Partially-Overlapping Local Subspaces"
authors: ["Irit Chelly", "Vlad Winter", "Dor Litvak", "David M. Rosen", "Oren Freifeld"]
date: 2020-06-16
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-08T19:03:43-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/CVF Conference on Computer Vision and Pattern Recognition"
publication_short: "CVPR"

abstract: "Background models are widely used in computer vision. While static-camera background (SCB) modeling is reasonably well-understood, moving-camera background (MCB) modeling remains a challenge. In this work, we propose a purely-2D, unsupervised, modular method that systematically overcomes these challenges. First, to estimate warps in the original video, we solve a joint-alignment problem while leveraging a certifiably-correct initialization. Next, we learn *both* multiple partially-overlapping local subspaces *and* how to predict registrations into these subspaces. Finally, at test time, we use these learned predictors to align a previously-unseen frame with the learned subspaces, and project it on a subset of those subspaces to obtain a background/foreground segmentation. We demonstrate that our method handles even large scenes with a relatively-free camera motion (provided the camera-to-scene distance does not change much), and that it not only yields state-of-the-art results on the original video, but also generalizes gracefully to previously-unseen videos of the same scene."

# Summary. An optional shortened abstract.
summary: ""

tags: ["background modeling", "moving-camera background modeling", "foreground/background separation"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://openaccess.thecvf.com/content_CVPR_2020/papers/Chelly_JA-POLS_A_Moving-Camera_Background_Model_via_Joint_Alignment_and_Partially-Overlapping_CVPR_2020_paper.pdf"
url_code: "https://github.com/BGU-CS-VIL/JA-POLS"
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: "https://www.youtube.com/watch?v=GYhP4lXQyQQ"

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
