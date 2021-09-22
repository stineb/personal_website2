+++
title = "Cold acclimation effects on photosynthesis"
date = 2020-01-31T11:36:26+01:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = []

# Project summary to display on homepage.
summary = "We investigate the apparent depression of photosynthesis in temperate and boreal forests in spring and after cold winters - a phenomenon that has been overlooked in global models."

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Optional external URL for project (replaces project detail page).
external_link = ""

# Links (optional).
url_pdf = ""
url_code = ""
url_dataset = ""
url_slides = ""
url_video = ""
url_poster = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

*You will investigate the apparent depression of photosynthesis rates in temperate and boreal forests in spring and after cold winters - a phenomenon that has been overlooked in global models. By combining remote sensing data, eddy covariance flux measurements, and modelling, you will find new solutions to an important challenge.*

Ecosystem-level photosynthesis (gross primary production: GPP) can be predicted using remotely sensed information on vegetation cover, local measurements of solar radiation and relatively simple models for the efficiency of photosynthesis (Ryu et al., 2019; Stocker et al., 2019). But one aspect of model-data mismatch stands out: The early-season increase in GPP is typically simulated to be around a month too early at some sites but not at others (Fig. 1). It will be your challenge to find out why and how to resolve this model deficiency.

![](/img/photocold.png)

*Fig. 1 Mean seasonal cycle of GPP aggregated for 14 sites where without early season overestimation of modelled GPP (a) and 13 sites with an apparent overestimation of early season modelled GPP (b).*

A hypothesis that may explain this phenomenon is that the photosynthetic apparatus is acclimated to the risk of frost damage in early spring, caused by conditions of low temperature and simultaneously high solar radiation. To prevent excessive light harvesting, photoprotective mechanisms are deployed by plants and lead to reduced photosynthetic carbon assimilation, and hence GPP. At locations with relatively mild winters and limited risk of frost, photoprotection may be less prevalent and photosynthesis rates are high already in the early season.

It will be your task to test this hypothesis. You will implement simple representations of cold-induced reduction of photosynthesis in our model in combination with remotely sensed vegetation cover and test revised predictions against a globally distributed set of site-level GPP measurements (eddy covariance). Your work will set the basis for extending this analysis using local multi-spectral imaging and identifying patterns between reflection data, the apparent GPP depression, and the light and temperature environment in the early season.

This thesis is a great starting point for working with large datasets of the terrestrial biosphere and modelling. Experience with working with R, Python or other data science tools are an advantage. You may start as soon as you like. Please contact me directly if you're interested: Prof. Benjamin Stocker, bestocke@ethz.ch

## Links

[`https://rpubs.com/stineb/photocold`](https://rpubs.com/stineb/photocold)

[`https://github.com/stineb/photocold`](https://github.com/stineb/photocold)
