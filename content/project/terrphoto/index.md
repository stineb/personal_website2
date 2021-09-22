+++
title = "New constraints on terrestrial photosynthesis"
date = 2020-02-11T09:36:01+01:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = []

# Project summary to display on homepage.
summary = "Developing a reduced-complexity land carbon balance model to use atmospheric constraints on terrestrial photosynthesis."

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

Photosynthesis of the terrestrial biosphere drives the land carbon cycle. For example, year-to-year variations in terrestrial photosynthesis are the dominant cause for year-to-year changes in land carbon uptake and the rate of increase in atmospheric CO2. Understanding terrestrial photosynthesis is thus important for understanding the fate of anthropogenic CO2 emissions and their effect on driving climate change. 

Unfortunately, terrestrial photosynthesis cannot be measured directly. Most available estimates are based on remote sensing observations of the vegetation cover, combined with models for the efficiency by which absorbed light is used for carbon assimilation. Recently, new methods have been developed to use alternative remotely sensed observations (e.g., sun-induced fluorescence) to estimate terrestrial photosynthesis. Also Dynamic Global Vegetation Models (DGVMs) provide estimates of terrestrial photosynthesis, but they don't use remotely sensed observations directly.

![](/img/terrphoto.png)
*Above: (left) spatial distribution of annual mean sun-induced fluorescence (SiF), a proxy for GPP; (right) spatial distribution of annual total GPP, mean across multiple remote sensing-based models. This illustrates the inconsisten spatial distribution (particularly the tropics-extratropics gradient) of remote sensing-based GPP estimates.*

Research in our group has revealed that these approaches yield inconsistent estimates in terms of (i) the spatial distribution of photosynthesis rates and (ii) the magnitude of year-to-year variability. The challenge that you will address in this project is to find new constraints to resolve this inconsistency. The use of atmospheric CO2 measurements holds great promise as a constraint, but requires an estimate of the net carbon balance (including gains by photosynthesis and losses by respiration and disturbance). In this project, you will establish this link. You will develop a reduced-complexity representation of the terrestrial carbon balance, based on DGVM outputs and a pulse-response representation of terrestrial carbon storage. This will be used to "translate" remote-sensing based terrestrial photosynthesis estimates into implied effects on atmospheric CO2 and its spatial and year-by-year variations. Like this, we will be able to subject  the contrasting remote sensing based estimates of terrestrial photosynthesis to a new test and find out which ones are more wrong than others.

This thesis is a great starting point for working with large datasets of the terrestrial biosphere and modelling. Experience with working with R, Python or other data science tools are an advantage. You may start as soon as you like.
