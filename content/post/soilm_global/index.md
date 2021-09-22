+++
title = "Identifying drought impacts in a data-rich world"
date = 2019-03-08T11:56:10+01:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []
categories = []

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects = ["internal-project"]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

We live in a data-rich world. Satellites are collecting information about the state of the Earth surface in ever more fine-grained resolution. CO2 and water exchange fluxes between the vegetation and the atmosphere are continuously measured at several hundred sites across the globe. And (almost) all of this data is being made easily accessible to researchers from any institution or country. This data revolution has created a playground for data analysis and a testbed for models with an unprecedented potential for addressing scientific challenges and resolving pressing questions. 

*How do droughts affect photosynthesis, vegetation productivity and the global carbon cycle?* is one such question. Remote-sensing based models are widely used for estimating terrestrial photosynthesis. These commonly use information about the greenness of the Earth surface, incoming solar radiation and some measure of dryness. Due to the limitation that soil moisture is particularly challenging to observe from satellites, these models have commonly resorted to using information only on the atmospheric dryness (vapour pressure deficit). In view of known physiological mechanisms by which plants respond to drying soils, the question is: Does vapour pressure deficit alone provide enough information to simulate drought impacts on vegetation?  

The advantage of our world’s data richness is that we now have more precise insights from observations to better uncover weaknesses in models. One such insight we gained in an earlier study (Stocker et al., 2018), where we isolated the soil moisture effect on photosynthesis from other drivers, including the (partly co-varying) vapour pressure deficit. By analysing patterns in the data from flux measurements and satellites, we found a clear additional effect by soil moisture that substantially reduces photosynthesis during “soil moisture droughts” - an effect that cannot be estimated when solely relying on information on vapour pressure deficit. It was an obvious question to ask whether the remote sensing-based terrestrial photosynthesis models, which do not account for soil moisture directly, can still accurately simulate photosynthesis during these, now well-defined drought periods. Freely accessible data and an open data sharing philosophy of the research community made it possible that within a short amount of time, we had all the necessary resources to start investigating. And soon thereafter, we had our Eureka moment: Indeed, all the models we investigated had a very clear relationship with the timing and magnitude of the apparent soil moisture stress we identified earlier. This is what we show in the paper, now published in *Nature Geoscience* (Stocker et al., 2019). 

This finding has implications not only for simulating vegetation productivity, but also for estimating the impacts of extreme events and the year-to-year variations of the terrestrial carbon balance. Dry and hot periods like last year’s summer in northern Europe can negatively affect the C balance of a whole continent and thereby accelerate the man-made increase in atmospheric CO2. Our new paper shows that the size of such anomalies, and therefore the magnitude of disruption of the C cycle, is substantially underestimated when the additional effect by soil moisture stress is neglected. This clearly points to the need for revising satellite-based monitoring of vegetation productivity and to develop new methods for including information on how soil moisture varies across space and time and how this affects vegetation productivity. Our findings come at a time when several groups are developing new methods to use remotely sensed information to estimate soil moisture. Resolving this challenge is important as with a changing climate, periods of drought may become more frequent, intense and prolonged and we need to have a better grasp of how this affects ecosystems and the carbon cycle. 

## References

**Stocker, B. D.**, Zscheischler, J. , Keenan, T. F., Prentice, I. C., Peñuelas, J. and Seneviratne, S. I. (2018), Quantifying soil moisture impacts on light use efficiency across biomes. *New Phytologist*, 218: 1430-1449. doi:10.1111/nph.15123 

**Stocker, B. D.**, Zscheischler, J. , Keenan, T. F., Prentice, I. C., Seneviratne, S. I. and Peñuelas, J. (2019), Drought impacts on terrestrial primary production underestimated by satellite monitoring. *Nature Geosci.* 