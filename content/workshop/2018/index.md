---
title: "R for trial and model-based cost-effectiveness analysis"
summary: 
tags:
- Workshop
date: "2018-07-09"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: 

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: 
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

## 11 July 2018, University College London <br><br>

{{% alert note %}}
<b>Venue</b>: Room G13 in <a href="https://goo.gl/maps/pzn4q1rjxU32">1-19 Torrington Place</a>, University College London, United Kingdom. <br><br>
{{% /alert %}}

## **Background and objectives**
This one-day workshop on the use of <tt>R</tt> for trial and model-based cost-effectiveness analysis (CEA) is jointly organised by a consortium of researchers at various institutions ([UCL](https://www.ucl.ac.uk/statistics/), [University of York](https://www.york.ac.uk/che/), [University of Oxford](https://www.herc.ox.ac.uk/) and [Bangor University](http://cheme.bangor.ac.uk/)), led by the [MRC Hubs for Trials and Methodology and Research Conduct-II](https://www.bristol.ac.uk/population-health-sciences/centres/conduct2/). The Scientific Committee include: Howard Thom, Gianluca Baio, Anthony Hatswell, Dyfrig Hughes, Chris Jackson, Marta Soares, Claire Williams, Nicky Welton, Padraig Dixon, Boby Mihaylova and Iryna Schlackow. 

Funding for the workshop has been provided by the [MRC Network of Hubs for Trials Methodology Research](https://www.methodologyhubs.mrc.ac.uk/) and the [UCL Research Group Statistics for Health Economics](https://www.ucl.ac.uk/statistics/research/statistics-health-economics/).

CEA is often performed using <tt>MS Excel</tt> but, despite its ease of use, <tt>MS Excel</tt> incurs the disadvantages of slow computational speed and a lack of transparency; our workshop aims to explore the use of <tt>R</tt> for CEA as an alternative. The aim of the workshop is to present a wide range of technical aspects, including a discussion of the many available add-on packages to help users get the most out of <tt>R</tt> for CEA. Presentations and public discussions address the computational and transparency advantages of <tt>R</tt> over <tt>MS Excel</tt> for CEA and for easing collaboration. The speakers have diverse experience in government (including [NICE](https://www.nice.org.uk/)), academia and industry. 
<br><br>

## **Final Programme**
### Session 1: Invited talks (1) - chair: Anthony Hatswell
- 9:30-9:45. [Howard Thom](http://www.bristol.ac.uk/social-community-medicine/people/howard-h-thom/index.html), University of Bristol. _Welcome._
- 9:45-10:15. [Gianluca Baio](http://www.statistica.it/gianluca). Department of Statistical Science, University College London. [_<tt>R</tt> you seriously saying we shouldn't use <tt>Excel</tt>?_](Baio.pdf)
<p style="margin-left: 0.0em;padding: 0 0em 1em 0;">
This talk will showcase some of the <tt>R</tt> packages recently developed to aid the work of modellers working in health economic evaluations. The motivation and general philosophy of a few packages will be briefly presented. Examples of their use/advantages over more established, but often non-optimal computational tools, such as <tt>MS Excel</tt> will be demonstrated. Link to relevant [web-applications](https://egon.stats.ucl.ac.uk/projects/).
</p>

- 10:15-10:35. [Marta Soares](https://www.york.ac.uk/che/staff/research/marta-soares/). Centre for Health Economics, University of York. [_Using <tt>R</tt> for Markov modelling: an introduction._](Soares.pdf)
<p style="margin-left: 0.0em;padding: 0 0em 1em 0;">
This talk introduces the use of <tt>R</tt> for generic decision modelling detailing some of the advantages and disadvantages of this software package in relation to others commonly used, such as <tt>MS Excel</tt>. In this talk, I also present generic <tt>R</tt> code for Markov modelling, probabilistic sensitivity analyses and value of information analyses (using Monte Carlo simulation). <tt>R</tt> code for [deterministic](Rcode_deterministic.R) and [probabilistic](Rcode_probabilistic.R) analysis.
</p>

- 10:35-11:15. [Boby Mihaylova](https://www.ndph.ox.ac.uk/team/boby-mihaylova) and [Iryna Schlackow](https://www.ndph.ox.ac.uk/team/iryna-schlackow). Health Economics Research Centre, Nuffield Department of Public Health, University of Oxford. [_A policy model of cardiovascular disease in moderate-to-advanced chronic kidney disease._](Schlackov_Mihaylova.pdf)
<p style="margin-left: 0.0em;padding: 0 0em 1em 0;">
This talk will present the design and structure in R of the SHARP CKD-CVD model, developed using the 5-years follow-up data of 10,000 patients with chronic kidney disease in the SHARP study. The model projects chronic kidney disease progression and cardiovascular complications and mortality using a set of multivariate risk, cost and QoL equations. We will demonstrate the <tt>R</tt> Shiny-based model interface to enable use by external analysts and will discuss issues related to model functionality and speed of~execution. [Paper](https://heart.bmj.com/content/early/2017/08/03/heartjnl-2016-310970) describing the model; model [interface](http://dismod.ndph.ox.ac.uk/kidneymodel/app/).
</p>

- 11:15-11:35. Coffee break.

### Session 2: Participants oral presentation session (3 speakers, 15 minutes each) - chair: Marta Soares
- 11:35-11:55. [Jeroen Jansen](https://metrics.stanford.edu/about-us/bio/jeroen-jansen), Innovation and Value Initiative. [_An open-source cost-effectiveness simulation model for rheumatoid arthritis in <tt>R</tt>._](Jansen.pdf)
<p style="margin-left: 0.0em;padding: 0 0em 1em 0;">
As part of the Open Source Value Project (OSVP), we developed a flexible open-source individual patient simulation model for rheumatoid arthritis (IVI-RA model). Alternative biologic treatment sequences, parameter and structural uncertainty, and decision framework (i.e.~cost-effectiveness of multi-criteria decision analysis) can be easily explored. The model facilitates dialogue between stakeholders about relevant clinical data, modelling approaches, and value perspectives. <tt>R</tt> and <tt>C++</tt> code is available in a GitHub repository, along with Shiny server user interfaces for a non-technical audience.
</p>

- 11:55-12:15. [Eline Krijkamp](https://www.erasmusmc.nl/3790579/art/members/e.krijkamp?lang=en), Erasmus MC. [_Introducing the Decision Analysis in <tt>R</tt> for Technologies in Health (DARTH) initiative._](Krijkamp.pdf)
<p style="margin-left: 0.0em;padding: 0 0em 1em 0;">
This talk will present an introduction to the tools and educational materials created by the [DARTH](http://darthworkgroup.com/) (Decision Analysis in <tt>R</tt> for Technologies in Health) collaboration. DARTH is a multi-institutional, multi-university effort aiming to develop transparent and open-source solutions to decision analysis in health. DARTH courses and tutorial papers cover diverse applications of <tt>R</tt> in health decision sciences, including decision trees, cohort models, and microsimulations. DARTH have also created <tt>OpenTree</tt>, an online graphical user interface for building decision trees and Markov models than can output code to <tt>R</tt>.
</p>

- 12:15-12:30. [Dyfrig Hughes](http://cheme.bangor.ac.uk/DyfrigHughesBiography). Centre for Health Economics & Medicines Evaluation, Bangor University. [_Health technology assessors' perspectives on <tt>R</tt>._](Hughes.pdf)
<p style="margin-left: 0.0em;padding: 0 0em 1em 0;">
This session will present the perspectives of members of NICE evidence review groups, AWMSG secretariat and SMC independent assessors on sponsor submissions using <tt>R</tt>. The skill requirements, confidence and expertise of these groups in using <tt>R</tt> will also be discussed.
</p>

- 12:30-13:30. Lunch.

### Session 3: Invited talks (2) - chair: Boby Mihaylova
- 13:30-13:50. Howard Thom, University of Bristol. [_Value of information analysis in <tt>R</tt>._](Thom.pdf)
<p style="margin-left: 0.0em;padding: 0 0em 1em 0;">
This session will cover the methods for value of information analysis that can be implemented in <tt>R</tt>, including linearization, brute force Monte Carlo simulation, parallel computing, meta-modelling, multilevel Monte Carlo and quasi Monte Carlo.
</p>

- 13:50-14:10. [Chris Jackson](https://www.mrc-bsu.cam.ac.uk/people/in-alphabetical-order/h-to-m/christopher-jackson/). Medical Research Council Biostatistics Unit, University of Cambridge. [_Continuous-time multi-state models for disease progression._](Jackson.pdf)
<p style="margin-left: 0.0em;padding: 0 0em 1em 0;">
This session will introduce the theory of modelling disease progression as a continuous-time multi-state process, and how this can be used in cost-effectiveness analysis. <tt>R</tt> software for continuous-time modelling of various patterns of observed data will be discussed. 
</p>

- 14:10-14:30. [Claire Williams](http://www.bris.ac.uk/social-community-medicine/people/claire-williams/index.html). Bristol Medical School: Population Health Sciences, University of Bristol. [_An overview of a suite of code and functions for CEA in <tt>R</tt> using continuous-time multi-state modelling._](Williams.pdf)
<p style="margin-left: 0.0em;padding: 0 0em 1em 0;">
This session will give a brief snapshot of the code already available in a tutorial paper detailing how to carry out Markov and semi-Markov modelling using the continuous-time multi-state modelling survival analysis framework. It will include how to carry out deterministic and probabilistic sensitivity analysis and appropriate graphical outputs. 
</p>

- 14:30-14:50. Coffee break

### Session 4: Discussion - chair: Gianluca Baio
- 14:50-15:05. Anthony Hatswell. [Delta Hat Analytics](http://deltahat.co.uk/); Department of Statistical Science, University College London. [_Existing frameworks for collaborative working._](Hatswell.pdf)
<p style="margin-left: 0.0em;padding: 0 0em 1em 0;">
This session will outline various ways of working currently used in collaborative efforts in the health economics and connected spheres. The pros and cons of each approach will be outlines, and how the use of <tt>R</tt> may be promoted under each of the scenarios.
</p>

- 15:05-16:20. Participant discussion.
- 16:20-16:30. Howard Thom. _Close and conclusions._
<br><br><br>

<img src="https://www.bristol.ac.uk/media-library/sites/social-community-medicine/images/mrc-conduct2-logo.png", width = "180", height = "320" style="float: left;margin-right: 20px;margin-top: 0px;margin-bottom:0px;"> 
<img src="http://cdn.ucl.ac.uk/silva/UCLDefaultLayoutV3/images/corp-identity-bright-blue.gif", width = "180", height = "310" style="float: right;margin-left: 20px;margin-top: 0px;margin-bottom:0px;"> 
<br><br><br><br>
