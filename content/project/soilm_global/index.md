+++
title = "Carbon-water coupling across scales"
date = 2019-03-08T11:46:14+01:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = []

# Project summary to display on homepage.
summary = "Soil moisture effects on the carbon cycle - from the local to global scales and the impact of drought extreme events"

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

## Summary of our research

In our [new paper published in *Nature Geoscience*](https://www.nature.com/articles/s41561-019-0318-6) (view it [here](https://www.nature.com/articles/s41561-019-0318-6.epdf?author_access_token=BGVLWmElvocQ1pE62QCTW9RgN0jAjWel9jnR3ZoTv0OyhWonkp6GWFgymRIu-XiwzwuX2z2Y2LYuKXkpzWa99FZSDRcHEaLWYZDRcaio1Et-soqame00xLPa-MvXHz_RVj455cGThJ-86CjHA2XimQ%3D%3D)), we identified a common bias in different state-of-the-art satellite-based estimates of terrestrial photosynthesis, and found that this bias is closely related to droughts and their apparent impact on the functioning of vegetation. In other words, common satellite-based vegetation monitoring methods underestimate the impact of droughts.

What are the implications of this bias for our understanding of the terrestrial C cycle and its year-to-year variability? We investigated this question using a new global implementation of the P-model (open-access code available [here](https://github.com/stineb/sofun)). Our results suggest that accurately capturing soil moisture stress in photosynthesis modelling is  crucial for estimating the year-to-year variability in vegetation productivity and the impacts of drought extreme events. Not capturing this effect accurately leads to a substantial underestimation of this variability and to a systematic underestimation of drought extreme event impacts on vegetation productivity.

However, in our simulations, the locally strong soil moisture effect on vegetation productivity and its variability does not translate into a similarly strong water-control on the global-scale variability in terrestrial gross primary productivity. This is due to the compensating effects of different continents that are not synchronously drought-stressed and tend to compensate each other. 

In view of a recent study by [Humphrey et al. (2018)](https://www.nature.com/articles/s41586-018-0424-4) who found a clear relationship between terrestrial water storage and the atmospheric CO2 growth rate, this raises a fundamental question about the evident water-carbon coupling at the global scale: Is it  an apparent phenomenon where terrestrial water storage is a proxy for some other factor that controls vegetation functioning? Or are we missing some element of plant access to water that has a longer memory and stronger year-to-year variability, so that the simulated compensating effects from different continents that we found would no longer neatly compensate each other at the global scale? This is an exciting lead for future research...

## Further links

- A [blogpost](/post/soilm_global/) written for [*Nature Ecology and Evolution - Behind the Paper*](https://natureecoevocommunity.nature.com/channels/521-behind-the-paper).
- A [press release](/files/pressrelease_soilm_global.pdf) written in collaboration with Natalie Sanders, Imperial College

## Data and code

- Model output data from site-scale and global P-model simulations are available on [Zenodo](https://zenodo.org/record/1423484#.XIJNAlNKjOQ).
- Code for the entire analysis and producing figures is available on [Zenodo](https://zenodo.org/record/2543324#.XIJNTVNKjOQ) and on [github](https://github.com/stineb/soilm_global). Compile (knit) RMarkdown file `knit_soilm_global.Rmd` for a full reproduction of results or `si_soilm_global.Rmd` for re-creating the Supplementary Information to our paper.
