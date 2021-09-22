+++
title = "MIND"  # Add a page title.
date = 2019-03-06T00:00:00  # Add today's date.
widgets = false  # Page type is a Widget Page.
summary = "Website for my SNF Eccellenza project"  # Add a page description.
+++

## Next-generation modelling of the biosphere – Including new data streams and optimality approaches

My 5-year *Eccellenza* Professorial Fellowship, funded by the Swiss National Science Foundation

<!-- Professorship for Computational Ecosystem Science, co-hosted at the [Institute of Agricultural Sciences, ETH Zürich](http://www.ias.ethz.ch/) and [Forest Dynamics, WSL Birmensdorf](https://www.wsl.ch/en/about-wsl/research-units/forest-dynamics.html)
 -->

Co-hosted at the [Institute of Agricultural Sciences, ETH Zürich](http://www.ias.ethz.ch/) and [Forest Dynamics, WSL Birmensdorf](https://www.wsl.ch/en/about-wsl/research-units/forest-dynamics.html)

Starting September 2019

<!-- The overarching aim of MIND and the new ETH/WSL Group for Computational Ecosystem Science is to develop new model and data fusion approaches to gain a mechanistic understanding of biogeochemical cycling in ecosystems, water-carbon coupling, and forest responses to climate change. We work at the intersection of Earth system science, ecophysiology, ecology, applied statistics, and high-performance computing and use the widest possible diversity of observational data.
 -->

The overarching aim of MIND is to develop new model and data fusion approaches to gain a mechanistic understanding of biogeochemical cycling in ecosystems, water-carbon coupling, and forest responses to climate change. We work at the intersection of Earth system science, ecophysiology, ecology, applied statistics, and high-performance computing and use the widest possible diversity of observational data.

A postdoc position to work with me on this project (see below 'Postdoc: Scaling from trees to the forest') is open now. A link to the ad and application is [here](https://apply.refline.ch/845721/7239/pub/1/index.html). 

<!-- ![MIND Eccellenza across scales](/img/dreamstime_m_76702519_verysmall.jpg) -->

<!-- ![](/img/tree_root_allocation2_small.jpg) -->

![MIND Eccellenza across scales](/img/mind_scales.png)


## Key questions

The functioning and structure of land ecosystems are fundamentally altered by a changing climate, increasing CO2, and altered in nutrient cycling. Yet, we are lacking robust predictions of impacts caused by expected global environmental change. This project addresses a set of key scientific challenges with the aim to develop novel predictive methods based on fundamental ecological principles, and to make use of the widest possible diversity of data streams to inform our predictions.

We are trying to answer three key questions:

* Will nutrients limit the land C uptake?
* What is the sensitivity of ecosystems to drought?
* How is tree growth and forest dynamics affected by changing resource limitations today?

## Allocation and resource limitations

Our primary target is to better understand and model **allocation**, that is the distribution of carbon assimilated by photosynthesis into growth in different plant organs (foliage, wood, roots), reserves, or export into the soil rhizosphere. Changes in CO2, nutrient, and water availability cause shifts in allocation, which in turn has important repercussions on ecosystem carbon cycling and, if general patterns exist, affects the functioning of the terrestrial biosphere and feeds back to man-made climate change. 

What we can observe at the small scale (from experiments, forest inventories, flux measurements, etc.) determines what is happening at the global scale. By addressing allocation from all angles, and by systematically integrating models and observational data, MIND targets a better understanding of the controls on allocation and improves our predictive ability to simulate  general patterns in allocation and its response to shifting in resource limitations and how this affects ecoystem dynamics and the terrestrial carbon balance.

![MIND Eccellenza across scales](/img/mind_scales_obs.png)

## Approach

We develop new modelling approaches for simulating vegetation functioning and structure, funded in **optimality principles**. Such principles predict, for example, how allocation and plant traits are governed by the environment under the premise that a given fitness criterion is optimised. Hence, optimality principles serve to simulate how key model parameters vary with the environment, rather than relying on fixed values for a pre-defined set of plant functional types - the common approach followed in first-generation vegetation models.
 
For code development, we work with a new modular vegetation modelling framework ([SOFUN](stineb.github.io/sofun)) and with the vegetation demography model [LM3-PPA](xxx) (collaboration with Dr. Ensheng Weng, NASA, USA).

We are devoted to an open science philosophy. For us, this means that we'll make all code and other outputs... 

- **Findable** by publishing on [*Zenodo*](zenodo.org/stineb) and other premanent repositories,
- **Openly accessible** through [*github*](github.com/stineb/mindproject), and
- **Reusable** through free open-source software packages (see for example [rpmodel](stineb.github.io/rpmodel)) and comprehensive documentation (see for example [SOFUN](stineb.github.io/sofun)).

## The project

This project will offer three fully funded positions:

- One postdoc, 3 years, starting Autumn 2019
- Two PhD students, 4 years, starting Summer/Autumn 2020

... addressing three objectives:

![](/img/mind_scales_projectorg.png)

### PhD 1: The nature of nutrient limitation 

Research will address three key questions:

- How does optimal allocation affect C and N cycling?
- How does soil fertility influence the carbon cycle?
- What controls the rates of N fixation and loss?

![](/img/mind_scales_nutrients.png)

We will use the Global Change Manipulation Experiments database (under development, collaboration with [Dr. Sara Vicca, PLECO, University of Antwerp](https://www.uantwerpen.be/en/staff/sara-vicca/)) and explore the observational constraints on alternative model formulations for simulating coupled carbon and nitrogen dynamics in terrestrial ecoystems. This work will make important advances on several fronts: Generating fundamental insights into ecosystem dynamics and biogeochemical cycles, exploring new territory in model-data fusion on the basis of observations from manipulation experiments, and developing a reusable and scalable model testbed as the basis of future community-driven model intercomparisons.


### PhD 2: Water-carbon coupling

The following key questions will be addressed:

- Will water-limited regions continue their greening trend?
- How can we simulate stomatal and biochemical limitations on photosynthesis during droughts?
- What is the apparent rooting zone water capacity and how is it controlled by climate and groundwater depth?

We will use data from ecosystem flux measurements and remotely sensed green vegetation cover to constrain new modelling approaches that are funded in ecohydrology and plant hydraulics. Research will lay the foundations for extending current-generation vegetation models beyond simulating the water balance in the topsoil: groundwater access and a varying rooting depth across climatic gradients are a key target for our predictions and are important quantities for understanding carbon-water couplings in the Earth system. For this research line, we will collaborate with [Stan Schymanski (LIST, Luxembourg)](https://www.list.lu/en/research/project/wave/).

### Postdoc: Scaling from trees to the forest

Our target questions are:

- Are forests thickening?
- How can we estimate forest growth from individual-based data (forest inventories and tree ring records)?
- How can we combine multiple data streams to detect allocation changes in forests today?

![](/img/mind_scales_objectiveC.png)

How does climate change alter forest dynamics and what are implications for the global carbon cycle and local ecosystem services? Increasing CO2, trends in nutrient inputs from atmospheric deposition, extending growing seasons and changing drought patterns affect tree growth and forest biomass in myriad ways. One of the open key questions is whether stimulated growth in a high-CO2 world is compensated by an accelerated tree life cycle and higher mortality.

*"Vor lauter Bäumen den Wald nicht mehr sehen"*  

... is a serios challenge (German for *Not seeing the wood for the trees*). Our research will find new solutions with a new generation of models and statistical approaches to keep the overview and distill the fundamental mechanisms. 

Forest inventories and other (typically individual-based) forest datasets hold an enormous amount of information. However, the connection from observable quantities to insights into tree-level processes and how these affect forest dynamics is difficult to make when relying on common statistical approaches. A new generation of Vegetation Demography Models connect a mechanistic resolution of photosynthesis, respiration, growth, and resource limitations with explicit age-structured forest dynamics. This opens new possibilities for combining data with our process-understanding in a Bayesian statistical approach - an opportunity that MIND will make use of.

For this research, we will use the LM3-PPA Vegetation Demography Model, in collaboration with [Dr. Ensheng Weng (NASA GISS)](https://www.giss.nasa.gov/staff/eweng.html).






















