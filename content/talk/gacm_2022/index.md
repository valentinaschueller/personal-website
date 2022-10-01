---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "A Simple Test Case for Error Reduction of Black-Box Coupling Schemes"
event: "9th GACM Colloquium 2022"
event_url: "https://colloquia.gacm.de/"
location: "Essen, Germany"
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "Black-box coupling libraries such as preCICE support sophisticated methods to enable accurate and efficient multiphysics simulations (e.g., regarding data mapping or coupling scheme acceleration).
However, sticking to standard coupling schemes can easily decrease the achievable convergence order of the numerical solution, specifically with respect to time integration; a phenomenon we call order degradation.
To understand these effects (and possible solutions), we want to study specifically the interaction of coupling schemes and time integration methods. <p>

In this talk, we present and analyze a simple test case of two masses connected with springs; we use it to isolate the impact of the coupling scheme on the overall accuracy and energy conservation of a partitioned simulation. We show issues arising for combinations of traditionally used coupling schemes and common time integration methods. We demonstrate that these two components interact with each other, which can lead to surprisingly good and bad results. Continuing the analysis, we confirm how Strang splitting and waveform iterations can reduce or even prevent order degradation. Additionally, we analyze their impact on energy conservation. <p>

Both Strang splitting and waveform iterations are discussed with respect to their applicability in full-scale multiphysics applications. We finally give an outlook on an extension of the test case to study the convergence of waveform iterations for subcycling and multirate time stepping. This enables us to also cover applications with a multiscale characteristic."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2022-09-22T15:50:00
date_end: 2022-09-22T16:10:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2022-10-01T15:30:29+02:00

authors: [Valentina Schüller]
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
url_slides: "presentation.pdf"

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
projects: ["fsi_coupling"]
---
