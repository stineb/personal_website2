---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "DGVM linearity"
summary: ""
authors: []
tags: []
categories: []
date: 2021-09-25T11:56:38+02:00

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

## Motivation 

Many processes that determine the links between C (input) fluxes and C pool sizes in DGVMs are formulated in a linear way, or at least in such a way as to imply "linear" model behavior. As a consequence, the relative change in fluxes should be equal to the relative change in pool size. Such model formulations are also termed as "source-driven". In contrast, "sink-driven" would imply that it's not the (input) fluxes that determine the change in pool sizes, but other limiting factors that are independent of input fluxes. This has also been formulated as a fundamental critique in the way current DGVMs are conceived and thus, at least partly, predetermine their projected land C balance changes in climate change scenarios.

The question is: How close are models actually from being fully sink-driven? Or in other words: How linear is their dynamics?

DGVMs have evolved over several generations, starting from C-only models with a big-leaf representation and average individuals in a stand, to models that represent a coupled C-nutrient cycling, and now to models that combine explicit representations of forest stand dynamics with biochemical cycling. All these modifications should increase the importance of feedbacks within the system that leads to deviations from a linear, strictly source-driven behavior.

## Preliminary results

![Relatinship of the relantive enhancement in NPP versus the relative enhancement in GPP, derived from CO2-only simulations of a set of Dynamic Global Vegetation Models. This shows a point density of data points representing individual gridcells of all models pooled. Their clustering around the 1:1 line indicates linearity in the relationship between GPP and NPP and implies a constant ratio of NPP:GPP.](/img/dgvmlin.png)
