---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "A LSTM model for GPP"
summary: ""
authors: []
tags: []
categories: []
date: 2021-09-25T11:56:58+02:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

This research emerges from a semester project for the Data Science Lab at ETH Zürich, a course of the Computer Science study programme. I supervised students Alexandru Meterez, Piersilvio de Bartolomeis, and Zixin Shelley Shu, all MSc students in Computer Scince at ETHZ. The results are currently written up as a manuscript.

## Motivation

Ecosystem-atmosphere exchange fluxes of water vapour and CO2 are continuously measured at several hundred of sites, distributed across the globe. The oldest running sites have been recording data since over twenty years. Thanks to the international FLUXNET initiative, these time series data are made openly accessible from over hundred sites and provided in a standardized format and complemented with measurements of several meteorological variables, plus soil temperature and moisture, measured in parallel. These data provide an opportunity for understanding ecosystem fluxes and how they are affected by environmental covariates. The challenge is to build models that are sufficiently generalisable in space. That is, temporally resolved relationships learned from one subset of sites should be used effectively to predict time series, given environmental covariates, at new sites (spatial upscaling). 

This is a challenge as previous research has shown that relatively powerful site-specific models can be trained, but predictions to new sites have been found wanting. This may be due to site-specific characteristics (e.g. vegetation type) that have thus far not been satisfactorily encoded in models. In other words, factors that would typically be regarded as random factors in mixed effects modelling, continue to undermine effective learning in machine learning models.

## Approach

We found that deep neural networks that learn temporal dependencies in the data (Long-Short Term Memory, LSTM) are well-suited for this prediction task. 


## Preliminary results

Our results indicate that spatially generalisable LSTM models outperform our mechanistic model (the P-model) in predicting GPP. 

![](/img/mlflx.png) 
*Benchmarking of the LSTM versus a "physical model" - the P-model. This shows the coefficient of determination for out-of-sample predictions at individual sites. Points above the 1:1 line (dashed) indicate that the LSTM outperforms the physical model.*