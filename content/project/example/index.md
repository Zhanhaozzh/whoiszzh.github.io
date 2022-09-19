---
title: The one-dimensional nozzle flow
summary: Numerical and analytical solutions of one-dimensional nozzle flow。
tags:
  - example
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: one-dimensional nozzle
  focal_point: Smart

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

The numerical solution is redundant for the problem of one-dimensional nozzle, because the closed form analytical solution can be derived directly from the formula. However, in order to verify the reliability of CFD simulation method, it is a better choice to select the flow problem with known analytical solution. This project is mainly to verify and practice McCormack's method.

McCormack method is a method that uses prediction step and prediction step skillfully to realize second-order accuracy calculation.

{{< figure src="code1.png" id="code 1" >}}
