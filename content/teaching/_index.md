---
title: Teaching
summary: Links to my teaching material
date: "2018-06-28T00:00:00Z"

reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?

# Optional header image (relative to `assets/media/` folder).
header:
  caption: ""
  image: ""
---

This page provides links to course materials that I created.

Courses I currently teach at ETH Zürich are listed [here](http://www.vvz.ethz.ch/Vorlesungsverzeichnis/dozent.view?dozide=10048316&semkez=2021W&ansicht=3&lang=en).


## Environmental Systems Data Science, D-USYS, ETH Zürich

MSc and PhD learn all steps along a typical data science workflow for research projects in Environmental sciences with a particular focus on machine learning applications. This includes contents ranging from workspace management, data mining, handling diverse data formats, programming, version control, data processing, model selection, various machine learning methods, model evaluation, and visualisation.

I created this as a new course in collaboration with Prof. Loic Pellissier and Prof. Joshua Payne for the Environemntal Sciences and Agricultural Sciences study programmes at ETH Zürich.

- Tutorial available [here](https://stineb.github.io/esds_book/)

---

## Machine learning for Eddy Covariance Data

This is a half-day workshop introducing PhD students in environmental sciences into basic concepts and implementations of machine learning workflows in R.

I created this course for the C2SM Summer School 2021.

- Tutorial available [here](https://stineb.github.io/ml4ec_workshop/)

---

<!-- ## Lecture Introduction to C cycle, MRes EEC, Imperial College London

I taught an introductory course to the (terrestrial) carbon cycle for Masters students of the MRes Evolution and Ecology course at Imperial College London. This corresponds to about 6 hours teaching plus exercises.
 
The teaching material is accessible as a PDF here:

* lecture notes 
    * [link](http://bstocker.net/wp-content/uploads/2016/09/intro_to_c_cycle_teaching_EEC_MRes_oct_2015_novid.pdf)
* The exercises are taught by working with an R script that implements a (heavily simplified) 1-box (onebox.R) and (surprisingly powerful) 2-box model (twobox.R) for the global carbon cycle. This, including example output (twobox.pdf), is accessible here:
    * [exercise material (link to problem sets and solutions on github)](https://github.com/stineb/teaching/tree/master/lab_imperial)
 
---
 -->

## Exercises for Introduction to the Carbon Cycle, lead by Prof. F. Joos, CEP, University of Bern

For the exercises of the Carbon Cycle lecture by Prof. Fortunat Joos, University of Berne, I developed a series of problem sets to guide students into programming and apply simple methods to develop box models that capture some of the basic characteristics of the carbon cycle. This is supposed to illustrate the principles of ocean-atmosphere CO2 exchange, and the ocean carbonate chemistry and how these processes affect the accumulation of fossil 2 in the atmosphere. Writing simple box models in R is supposed to serve as a general introduction to programming (loops, conditional statements, input/output) and should allow students to play with their models and seize the effect of future emission pathways on the carbon cycle.
 
| Lesson                         | problems | data       | solutions |
|------                          |----      |----        |----       | 
| First steps in R               | [link](/files/ex1.pdf) | [link](https://github.com/stineb/teaching/blob/master/lab_bern/co2_monthly_maunaloa.txt)   | [link](https://github.com/stineb/teaching/blob/master/lab_bern/solution_carbon_cycle_3.R) |
| 1-Box model for the atmosphere | [link](/files/1box.pdf) |            | [link](https://github.com/stineb/teaching/blob/master/lab_bern/solution_carbon_cycle_4.R) |
| Farquhar photosynthesis model  | [link](/files/farquhar.pdf) |            | [link](https://github.com/stineb/teaching/blob/master/lab_bern/farquhar_c3_photo.R) |
| 2-Box Atmosphere-Ocean model   | [link](/files/2box.pdf) |            | [link](https://github.com/stineb/teaching/blob/master/lab_bern/2box.R) |