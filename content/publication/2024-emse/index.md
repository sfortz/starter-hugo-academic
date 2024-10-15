---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "VaryMinions: Leveraging RNNs to Identify Variants in Variability-intensive Systems’ Logs"
authors:
  - admin
  - Paul Temple 
  - Xavier Devroey 
  - Patrick Heymans
  - Gilles Perrouin
date: 2024-06-15
doi: "10.1007/s10664-024-10473-5"

# Schedule page publish date (NOT publication's date).
publishDate: 2024-10-15

# Publication type: paper-conference, article-journal, article-newspaper, book, chapter, masters-thesis, preprint, report, thesis, webpage (from CSL standard)
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "In *Empirical Software Engineering*"
publication_short: "In *EMSE*"

abstract: "From business processes to course management, variability-intensive software systems (VIS) are now ubiquitous. One can configure these systems’ behaviour by activating options, e.g., to derive variants handling building permits across municipalities or implementing different functionalities (quizzes, forums) for a given course. These customisation facilities allow VIS to support distinct relevant customer requirements while taking advantage of reuse for common parts. Customisation thus allows realising both scope and scale economies. Behavioural differences amongst variants manifest themselves in event logs. To re-engineer this kind of system, one must know which variant(s) have produced which behaviour. Since variant information is barely present in logs, this paper supports this task by employing machine learning techniques to classify behaviours (event sequences) among variants. Specifically, we train Long Short Term Memory (LSTMs) and Gated Recurrent Units (GRUs) recurrent neural networks to relate event sequences with the variants they belong to on six different datasets issued from the configurable process and VIS domains. After having evaluated 20 different architectures of LSTM/GRU, our results demonstrate that it is possible to effectively learn the trace-to-variant mapping with high accuracy (at least 80% and up to 99%) and at scale, i.e., identifying 50 variants using 5000+ traces for each variant."

# Summary. An optional shortened abstract.
summary: ""
tags: [Configurable processes, Recurrent neural networks, Variability-intensive systems, Variability mining, Software product lines]
categories: []
featured: false

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
---
