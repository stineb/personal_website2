+++
title = "The Fertility Question: How do soil nutrients influence the carbon cycle?"
date = 2015-06-05T13:31:09+01:00
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

A general notion of “soil fertility” is commonly left unaccounted for in models of the terrestrial biosphere and has received relatively little attention in carbon cycle science. This changed since the presentation of results by Vicca et al. (2012) and Fernandez-Martinez et al. (2014).

Using data from forests around the globe where gross primary productivity (GPP) has been measured in parallel to changes in ecosystem biomass storage, these authors showed that forests produce biomass more efficiently on fertile soils.
This efficiency can be quantified as the ratio of biomass production (BP) to GPP. Two factors affect this ratio. First, autotrophic respiration (Ra) – the C cost of maintaining cellular function (maintenance respiration) and synthesising new tissue (growth respiration). This factor has been shown previously to cause relatively large variations in CUE (= NPP/GPP = (GPP-Ra)/GPP) due to effects of forest stand age, climate, and forest type. However, Ra doesn’t appear to vary with soil fertility (Fernandez-Martinez et al., 2014). The second factor that determines the ratio of BP:GPP is the amount of C exported to the soil (Cex). There is also a third factor, the production of volatile organic compounds, VOCs, that has been shown to significantly affect the plant’s C budget, especially under heat stress. Let’s ignore this for now. Traditionally, Cex hasn’t commonly been separated out from NPP, and is often left unquantified in field studies. However, more recent research has shown that up to around 20% of NPP may be consumed by Cex. 

We can now write:

*new*:    BP = GPP – Ra – Cex – VOC

*old*:    NPP = GPP – Ra

In parallel to the observed variations on BP:GPP by Vicca et al. (2012) and Fernandez-Martinez et al. (2014), they also found that the ratio of fine root to total biomass was almost three times higher in nutrient poor than in nutrient rich forest, and that the LAI per unit fine-root biomass is twice as large in nutrient rich forests. This is perfectly in line with earlier studies reporting general and strong variations of these allocation patterns along soil fertility gradients (Poorter et al., 2012). Apparently, on low-fertility soils, plants invest more C below-ground. C allocation thus dynamically adjusts in response to soil fertility – a mechanism ignored by today’s generation of global vegetation and terrestrial carbon cycle models altogether.

But where does Cex go and what is its function? Clearly, growing more roots serves a better soil exploration in the search for nutrients required for plant growth (apart from accessing soil moisture and maybe even ground water). In contrast, the exuded C (Cex) may be consumed by an array of soil organisms with the pleasant effect of improving nutrient availability for the plant – either directly (N2-fixing bacteria in root nodules; mycorrhizal fungi living on the root tips) or indirectly (free-living N2-fixing bacteria in the soil; other heterotrophs that accelerate soil turnover and N mineralization, so called priming). The importance of these effects are only now becoming to be fully appreciated and integrated into models of the terrestrial C budget, and a quantitative and mechanistic link to soil fertility is yet to be established – the goal of my work here in the group of Colin Prentice.

The lesson from all this (relatively new) research described above is that the nutrient availability appears to be under clear biological control, but that their acquisition comes at a cost to the plant: C used below-ground (root production and Cex) is missing for above-ground growth and the competition for light. We can say that this cost is dependent on the soil fertility and implies that there must be a soil fertility-dependent balance of above- versus below-ground allocation that is optimal for the plant with respect to maximizing its “fitness”. Such considerations are the target of theoretical studies that bear great potential in providing quantitative predictions of C allocation (Mäkelä et al., 2008; Franklin et al., 2014).

Now two more points that need clarification: 1. What is soil fertility? and 2. How does the concept of soil fertility relate to the classical view of nutrient limitation?

Soil fertility is often indirectly defined by “where plants grow well”. This may also be expressed as “where nutrients are easily available” a condition affected by the soil chemistry and structure in ways that are difficult to describe and predict mechanistically, especially at a global scale. However, there is a set of parameters often measured, directly or indirectly, in the field that appear to determine “soil fertility”. These include pH, the cation exchange capacity, available N and P, C:N ratio of soil organic matter, C content, and the texture (fractions of sand, clay, loam, silt). The soil type itself is something like a “syndrome” expressed by typical values of these measurable parameters, but may also provide readily accessible information. Soil formation is determined by climate, parent material, and time. This is reflected by large scale gradients of soil fertility across different biomes – from infertile, acidic soils in boreal regions; fertile, C rich soils in seasonally cold grasslands where decomposition is inhibited; N-poor but otherwise relatively fertile young soils in temperate region; to highly weathered, i.e. P-poor, old soils in tropical lowlands. Sorption of P to surfaces in the particular soil matrix in tropical soils, leaching of mobile P under high precipitation, and very small inputs through atmospheric deposition gradually deplete soils of P over time in the tropics, while N is gradually added by abundant N fixing organisms. As opposed to such old tropical lowland soils, soils at high latitudes are younger (previous glaciation!) and P is still more readily available, whereas constraints to N fixation prevent its accumulation.

![](/img/hwsd.png)

*Figure HWSD Global Soil Quality – constraints on nutrient availability (Fisher et al., 2008). Accessed from [http://databasin.org/](http://databasin.org/datasets/20dcb500682c4ec891e2fc881c2ed65c).*

The dominant pattern of N limitation in boreal and temperate biomes and P limitation in tropical biomes is also revealed by classical fertilization experiments. Added N generally stimulates plant growth at higher latitudes (but not so for added P), and vice versa at low latitudes. Such a nutrient limitation concept is implemented in different ESMs: Either GPP or NPP is capped and further plant growth is halted if nutrients (usually just N, sometimes also P) becomes unavailable. This leads to substantially lower predictions of C uptake under rising CO2 and the important negative feedback to anthropogenic climate change (through CO2 emissions) disappears almost completely when applying such models (Wieder et al., 2015). But doesn’t this disagree with the widely observed, and theoretically plausible biological control on nutrient availability as discussed above? I would argue that yes indeed, these predictions are add odds with them! This Liebig Law-type view of nutrient limitation also fails to explain the clear CO2 stimulation of growth under high-N as well as low-N conditions. So how can the observed variations of BP:GPP with soil fertility and nutrient limitation be reconciled?

In my understanding (following the understanding of others of course), nutrient limitation is not a fixed cap, but under biological control, expressable as a “C cost for nutrient uptake”. On infertile soils, this cost is generally higher. Be it because of low pH (which directly affects soil chemistry, nutrient availability and microbial activity) or because of soil texture (affecting nutrient retention, resistance to root growth, etc.) or other parameters. If an ecosystem is “limited” by, for example, N (i.e., no growth stimulation by adding P or elevating CO2), then the cost for taking up N is infinite. In that respect, the concept of a C cost (reflected in Cex and BP:GPP) is a generalization of the Liebig-type limitation concept, and is also able to integrate other factors that determine soil fertility (cost is as a function of pH, …).

So is nutrient limitation just a question of C cost and thus energy availability? (Radiation energy is converted by photosynthesis to labile C, the fuel for any plant function). Maybe this is indeed the case for limitation by N. Obviously, there is no limit (other than energy) to biological control of N availability through converting N2 into reactive forms. In view of the ever-increasing N inputs through atmospheric deposition, reactive N, previously created by fossil fuel combustion, N limitation even seems to be relieved “for free” in affected ecosystems. This is different for P limitation. P doesn’t have a gaseous phase and is merely rock-derived. Also atmospheric deposition is very small, and the acceleration of anthropogenic inputs of reactive P lags behind the one for N (Penuelas et al., 2013). Once made available to plants, P recycling in ecosystems is highly conservative: only very small losses occur because it’s very costly for plants to accrue new P once it’s lost. The N cycle is much more leaky – N seems to be cheaper. Up to 25% of BP is fuelled by new inputs in the tropics (Cleveland et al., 2013). Taken together, it seems like enhanced demand for N under increasing CO2 should be met. No? On the other hand, P may impose much more of a limitation to future C uptake.

The goal of my research is to investigate the C cost for nutrient uptake. What soil fertility parameters have to be taken into account to accurately predict observed gradients in biomass production efficiency and above- versus below-ground allocation patterns. And what is the implication of biological control – taking into account such C cost effects – on the future of the land C sink? Please stay tuned …

## References

Vicca, S.; Luyssaert, S.; Peñuelas, J.; Campioli, M.; Chapin, F. S.; Ciais, P.; Heinemeyer, A.; Högberg, P.; Kutsch, W. L.; Law, B. E.; Malhi, Y.; Papale, D.; Piao, S. L.; Reichstein, M.; Schulze, E. D. & Janssens, I. A.Fertile forests produce biomass more efficiently Ecology Letters, Blackwell Publishing Ltd, 2012, 15, 520-526

Fernandez-Martinez, M.; Vicca, S.; Janssens, I. A.; Sardans, J.; Luyssaert, S.; Campioli, M.; Chapin III, F. S.; Ciais, P.; Malhi, Y.; Obersteiner, M.; Papale, D.; Piao, S. L.; Reichstein, M.; Roda, F. & Penuelas, J. Nutrient availability as the key regulator of global forest carbon balance Nature Climate Change, 2014, 4, 471-476

Poorter, H.; Niklas, K. J.; Reich, P. B.; Oleksyn, J.; Poot, P. & Mommer, L. Biomass allocation to leaves, stems and roots: meta-analyses of interspecific variation and environmental control New Phytologist, 2012, 193, 30-50

Mäkelä, A.; Valentine, H. T. & Helmisaari, H.-S. Optimal co-allocation of carbon and nitrogen in a forest stand at steady state New Phytologist, 2008, 180, 114-123

Franklin, O.; Näsholm, T.; Högberg, P. & Högberg, M. N. Forests trapped in nitrogen limitation – an ecological market perspective on ectomycorrhizal symbiosis New Phytologist, 2014, 203, 657-666

Wieder, W. R.; Cleveland, C. C.; Smith, W. K. & Todd-Brown, K. Future productivity and carbon storage limited by terrestrial nutrient availability  Nature Geosci, 2015, 8, 441-444

Peñuelas, J.; Poulter, B.; Sardans, J.; Ciais, P.; van der Velde, M.; Bopp, L.; Boucher, O.; Godderis, Y.; Hinsinger, P.; Llusia, J.; Nardin, E.; Vicca, S.; Obersteiner, M. & Janssens, I. A. Human-induced nitrogen–phosphorus imbalances alter natural and managed ecosystems across the globe Nat Commun, 2013, 4

Cleveland, C. C.; Houlton, B. Z.; Smith, W. K.; Marklein, A. R.; Reed, S. C.; Parton, W.; Del Grosso, S. J. & Running, S. W. Patterns of new versus recycled primary production in the terrestrial biosphere Proceedings of the National Academy of Sciences, 2013, 110, 12733-12737

Fischer, G., F. Nachtergaele, S. Prieler, H.T. van Velthuizen, L. Verelst, D. Wiberg, 2008. Global Agro-ecological Zones Assessment for Agriculture (GAEZ 2008). IIASA, Laxenburg, Austria and FAO, Rome, Italy.