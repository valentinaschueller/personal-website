---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Coupled Groundwater-Surface Flows"
summary: "I am studying the numerical properties of coupling algorithms for flood prediction models. This is a project in collaboration with Philipp Birken and Andreas Dedner."
authors: [valentina]
tags: [coupling,multiphysics,precice,Python,equation coupling,waveform iterations]
categories: []
date: 2023-06-15T16:47:47+02:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Photo by [Joshua J. Cotten](https://unsplash.com/@jcotten) on [Unsplash](https://unsplash.com/photos/green-trees-near-body-of-water-during-daytime-zlqmr4mESS8)"
  focal_point: ""
  preview_only: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

share: false
slides: ""
---

In this project, we are analyzing coupling algorithms for the Richards equation coupled to the shallow water equations (SWE).
These are nonlinear partial differential equations which can model groundwater and surface flows, respectively.
Coupling them yields a model that can simulate effects of water management and flooding on the water table and aquifer.[^1]
Particularly, I am working on a fully discrete and continuous analysis of Dirichlet-Neumann Waveform Relaxation (DNWR) for a linearized, coupled Richards-SWE model.
Here I have used methods developed by [Monge & Birken, 2018](https://doi-org.ludwig.lub.lu.se/10.1007/s00466-017-1511-3) and [Gander, Kwok & Mandal, 2014](https://doi-org.ludwig.lub.lu.se/10.1007/978-3-319-18827-0_51).

I have developed a [test code for analysis verification](https://github.com/valentinaschueller/richards-swe-coupling).
Additionally, I have reworked and extended an [implementation of the fully nonlinear model](https://gitlab.maths.lu.se/robertk/coupling).
Both are written in Python, using [DUNE](https://dune-project.org/) to generate the discretization and [preCICE](https://precice.org/) for coupling.

***Collaborators:** [Philipp Birken](https://www.maths.lu.se/staff/philipp-birken) and [Andreas Dedner](https://warwick.ac.uk/fac/sci/maths/people/staff/andreas_dedner/).*

[^1]: Bastian, P. et al. (2012). Adaptive Modelling of Coupled Hydrological Processes with Application in Water Management. In: Günther, M., Bartel, A., Brunk, M., Schöps, S., Striebel, M. (eds) Progress in Industrial Mathematics at ECMI 2010. Mathematics in Industry, vol 17. Springer, Berlin, Heidelberg. https://doi-org.ludwig.lub.lu.se/10.1007/978-3-642-25100-9_65

