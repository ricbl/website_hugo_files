---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "VR-GAN"
summary: ""
authors: []
tags: []
categories: []
date: 2019-09-29T16:50:07-06:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Bottom"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "http://github.com/ricbl/vrgan"
url_pdf: "https://arxiv.org/abs/1908.10468"
url_slides: ""
url_video: ""
url_poster: "files/miccai2019_poster.pdf"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
<div style="text-align: justify "> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Project about training explainable regression deep models. We developed a method that uses an adversarial loss to train an explainable regressor, whose outputs are explained by a generator. The generator produces differences maps that can be added to input images to answer the question "What would this image look like if it was associated with this other regression target?". The algorithm was applied to chest x-rays and regression targets related to the severity of chronic obstructive pulmonary disease (COPD), and the resulting difference maps highlighted regions of the image that radiologists use when identifying the presence of COPD in chest x-rays. This projected will be presented at the MICCAI 2019 main conference in Shenzhen, China, on September 16th. </div>