---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Monitoring Numerical Climate Simulations. A Tool for the EC-Earth Climate Model."
authors: [Valentina Schüller]
date: 2020-09-12
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-10-11T17:07:51+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Climate model experiments are time consuming numerical simulations. Real-time monitoring of experiments allows to spot problems in the model performance early on. Conspicuous results or changes in the computational performance can be detected at runtime. Users can then interrupt the experiment, thus saving computational resources. While in-depth and model-independent analysis tools exist for finalized and post-processed output, monitoring is model-specific and uses raw output data. With changing configurations and experiment setups, monitoring tools must be extendable and should not be limited to individual model components. For the latest version of the European community Earth system model EC-Earth, a Python based monitoring application has been developed. The tool tracks the physical and computational performance of ongoing simulations based on established metrics and diagnostics in climate science. This thesis presents
design considerations and decisions, as well as the status quo of its feature set. Although the concrete implementation is optimized for EC-Earth 4, the software design and choice of monitoring diagnostics is of broader relevance. The monitoring tool’s capabilities are shown and discussed based on an exemplary and realistic simulation."

# Summary. An optional shortened abstract.
summary: "My BSc thesis, describing the design and development approach behind the new EC-Earth 4 monitoring tool."

tags: [climate science]
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
projects: [ece_monitoring]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
share: false
---
