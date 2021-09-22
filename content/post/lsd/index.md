+++
title = "LSD Heatscatter with ggplot"
date = 2019-05-13T23:19:08-07:00
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

I love the [`heatscatter()`](https://www.rdocumentation.org/packages/LSD/versions/4.0-0/topics/heatscatter) function from the [LSD R package](https://cran.r-project.org/web/packages/LSD/index.html). I've even used it for my own publications (see Figs. 2 and 7 in [Stocker et al. 2017](https://nph.onlinelibrary.wiley.com/doi/10.1111/nph.15123)). Since having written this paper and creating the figures I've (finally) moved to using ggplot. Unfortunately, `heatscatter()` creates a plot in base R. 

Googling, I found no satisfying solution. What is described on [this blog](http://auguga.blogspot.com/2015/10/r-heat-scatter-plot.html) does't really do the trick. 

I tried another approach. I forked the [LSD library into my github](https://github.com/stineb/LSD) and hacked an additional argument into the `heatscatter()` function as:

`ggplot` a logical: if `TRUE` uses the ggplot2 library to create plots. Defaults to `FALSE`.

When set to `TRUE`, the function returns a ggplot object. For example the following bit of code ...
```
gg <- heatscatter(mdf$lue_mod, mdf$lue_obs, xlab = "Modelled", ylab = "Observed", ggplot = TRUE)
gg + lab(title = "Example")
```
... prints a simple plot, by default (and hard-coded), using ggplot's `theme_classic()`. This looks like this:

![](/img/ggplot_heatscatter_example.png)

That's it. A direct link to the hacked `heatscatter()` function is [here](https://github.com/stineb/LSD/blob/master/R/LSD.heatscatter.R).

Credits to the halluzinogenic LSD package developer Bjoern Schwalb!