---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Waveform Relaxation for Coupled Groundwater and Surface Flows"
event: "13th Workshop on Parallel-in-Time Integration"
event_url: "https://time-x.eu/pint-2024/"
location: "Bruges, Belgium"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2024-02-06T11:00:00
#date_end: 2022-09-22T11:30:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2024-02-01T15:30:29+02:00

authors: [valentina, Philipp Birken, Andreas Dedner]
tags: [waveform iterations, Strang splitting, energy conservation, order degradation]

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides: "PinT24_Presentation.pdf"

url_code:
url_pdf:
url_video:

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
projects: ["richards_swe"]
share: false
---

Water management projects such as stream bed re-naturalization affect the water table, which is relevant, e.g., for flood prediction. These physical processes can be modeled by coupling the Richards equation for groundwater flow to a shallow water model for rivers or lakes ([Bastian et al., 2012](https://doi-org.ludwig.lub.lu.se/10.1007/978-3-642-25100-9_65)). We analyzed the fully discrete, linearized formulation of this coupling problem, yielding an optimal choice of the relaxation parameter for sequential Dirichlet-Neumann iterations. Here we followed the techniques previously established in [Monge & Birken, 2018](https://doi-org.ludwig.lub.lu.se/10.1007/s00466-017-1511-3). This analysis is closely linked to parallel Dirichlet-Neumann iterations, which are a special case of parallel-in-time waveform relaxation. Waveform relaxation methods have been extensively studied in continuous or semi-discrete formulations. As we will show in this talk, the fully discrete analysis—corresponding to the actual implementation in a numerical model—can give significantly different results. Our theoretical analysis is supported by numerical results for a fully nonlinear test case using [DUNE](https://dune-project.org/) and [preCICE](https://precice.org/).
