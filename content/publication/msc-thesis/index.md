---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Schwarz Waveform Relaxation for a Single Column Climate Model"
authors: [Valentina Schüller]
date: 2023-03-29
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-06-02T17:07:51+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Typical algorithms used to couple atmosphere and ocean models are computationally efficient but mathematically inconsistent, thus introducing a numerical error. Schwarz waveform relaxation is an iterative coupling method to restore consistency at the interface, allowing to investigate the magnitude and physical implications of this error. The large computational cost of Schwarz waveform relaxation prevents in-depth numerical studies with coupled general circulation models. On the other hand, the theoretical analysis of highly idealized problems is insufficient to draw conclusions about general circulation models. In this master’s thesis, a coupled atmosphere-ocean model of intermediate complexity, the one-dimensional EC-Earth AOSCM, was modified to support different coupling schemes used in operational climate models, as well as Schwarz waveform relaxation. This makes it a tool to bridge the gap between previous theoretical and numerical studies. Multi-day simulations in this new setup illustrate how physical parameterizations in the atmosphere react to changes in interface boundary conditions at the sea surface. Small variations in sea surface temperature can yield potentially large differences between standard coupling algorithms and the more accurate result of the Schwarz method. The EC-Earth AOSCM shares a significant amount of code and architecture with the EC-Earth 3 climate model. This similarity allows us to address algorithmic aspects and implementation challenges for iterative coupling schemes in climate modeling."

# Summary. An optional shortened abstract.
summary: "My MSc thesis on Schwarz waveform relaxation in the EC-Earth Single Column Model."

tags: [waveform iterations, climate science, multiphysics, equation coupling, Python]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
share: false
---
