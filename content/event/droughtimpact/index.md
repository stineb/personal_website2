---
title: Master thesis - Drought impact prediction

# event: Wowchemy Conference
# event_url: https://example.org

location: ETH Zentrum, Zürich and IBM Research Europe, Rüschlikon
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: Satellite image forecasting for drought impact early warning
abstract: "To forecast the dynamics of vegetation greenness and drought-induced early defoliation, you will develop a machine learning-based algorithm. The aim is to predict when and where extreme drought conditions lead to damage of leaves and trees. The focus is on temperate forests in Europe, and you will be benefit from the computational resources and data science support by the AI & Physics for Climate Impact group at IBM Research Europe, Zurich."

# Talk start and end times.

# #   End time can optionally be hidden by prefixing the line with `#`.
# date: "Anytime"
# date_end: "2030-06-01T15:00:00Z"
# all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2022-03-08T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: B. Stocker'
  focal_point: Right

links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- example
---

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}} -->

**Main supervision:** Prof. Dr. Benjamin Stocker
**Co-supervision:** Dr. Thomas Brunschwiler

Recent hot and dry summers in Europe have led to impacts on the functioning and structure of forests. Combined heat and drought stress led to wide-spread canopy defoliation ('browning' or 'early wilting') and tree mortality. The challenge facing multiple stakeholders now is to understand where and when impact thresholds were exceeded in the past years and to anticipate forest responses to future climatic extreme events.

Earth observation data has yielded a wealth of information about the state of vegetation and browning events at a resolution of tens of meters. These data have revealed patterns of a distinct heterogeneity of impacts across space and have yielded information about the timing of impacts over the past decades and effects of repeated stress by droughts in consecutive years. This data-richness, combined with novel machine learning methods, opens a potential for building predictive models, learning from observed impacts and their relationship with environmental drivers. But the combination of temporal and spatial dependencies in the data calls for specifically tailored model architectures, informed by knowledge of ecosystem processes across varying environmental conditions across the landscape.

You will will develop new solutions to address this challenge. The project will be conducted in collaboration with the IBM AI & Physics for Climate Impact group, based in Rüschlikon, Switzerland, and you work within their cloud computing and data infrastructure. This thesis will set the basis for an online early warning platform that will enable periodically updated near-term drought-impact forecasts beyond the project's lifetime. The prediction target is vegetation greenness, measured by the normalized difference vegetation index (NDVI). You will proceed by combining multiple data sets for analysis-readiness; developing a suitable method for predicting NDVI time series across space; and developing a reusable workflow and online platform as the basis for an operational near-term impact forecasting and early warning, implemented in the future.