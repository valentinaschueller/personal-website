---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Coupling Algorithms in the EC-Earth AOSCM"
summary: "Adapting the single column version of the EC-Earth climate model to study atmosphere-ocean coupling."
authors: [valentina]
tags: [coupling,multiphysics,climate science,ec-earth]
categories: []
date: 2023-06-15T16:47:47+02:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Photo by Patrick Kelley (License: [CC BY 2.0])(https://creativecommons.org/licenses/by/2.0/deed.en)"
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

I started working with the EC-Earth coupled atmosphere–ocean single-column model ([Hartung et al., 2018](https://doi.org/10.5194/gmd-11-4117-2018)) during my [master's thesis]({{<ref "/publication/msc-thesis">}}).
This is a version of the [EC-Earth global climate model](https://ec-earth.org/) which is useful for model development, particularly regarding physics parameterizations in the atmospheric and oceanic boundary layers.
In my work, I have created scripts and workflows to study the impact of different coupling algorithms on model output.
My master's thesis covers pure atmosphere-ocean coupling, we are working to include other models as well (e.g., the sea ice model [LIM3](https://doi.org/10.5194/gmd-8-2991-2015)).

The goal here is to make the EC-Earth AOSCM a tool for coupling algorithm development in climate models.
See the [corresponding GitHub repository](https://github.com/valentinaschueller/ece-scm-coupling) for further information.

***Collaborators:** [Philipp Birken](https://www.maths.lu.se/staff/philipp-birken); [Florian Lemarié](https://membres-ljk.imag.fr/Florian.Lemarie/) & [Eric Blayo](https://membres-ljk.imag.fr/Eric.Blayo/) ([AIRSEA Group](https://team.inria.fr/airsea/en/), INRIA Grenoble); [Dynamic Meteorology Group at MISU](https://www.su.se/english/research/research-groups/dynamic-meteorology).*
