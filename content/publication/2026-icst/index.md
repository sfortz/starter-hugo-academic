---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Toward Live Noise Fingerprinting for Discrepancy Analysis in Quantum Software Engineering"
authors:
  - Avner Bensoussan
  - Elena Chachkarova
  - Karine Even-Mendoza
  - admin
  - Vasileios Klimis
  - Mohammadreza Mousavi
date: 2026-04-03
doi: #"10.1145/3472674.3473980"

# Schedule page publish date (NOT publication's date).
publishDate: 2026-04-03

# Publication type: paper-conference, article-journal, article-newspaper, book, chapter, masters-thesis, preprint, report, thesis, webpage (from CSL standard)
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "In the *Short Papers, Vision and Emerging Results* track of the *19th IEEE International Conference on Software Testing, Verification and Validation*"
publication_short: "In the *Short Papers, Vision and Emerging Results* track of *ICST 2026*"

abstract: "Contemporary quantum computers are inherently noisy, posing significant challenges for the development and testing of quantum software. Simplified or outdated noise assumptions can lead to incorrect assessments of program correctness, obscure debugging, and hinder cross-platform portability, creating a critical quantum software development gap. Providing accurate, practical noise characterisation is challenging as traditional reconstruction methods scale exponentially and rapidly become outdated. In this vision paper, we address this gap via a novel classical shadow tomography-based pipeline, SimShadow, enabling efficient, continuously updatable noise fingerprinting from empirical observations, suitable for integration into quantum software development workflows, including testing and validation. We prototyped the pipeline to investigate fingerprints’ ability to capture structured, interpretable noise and cross-platform discrepancies affecting quantum programs’ behaviour to support realistic testing and debugging in future tools. Our evaluation with Qiskit and Cirq under widely used hardware-informed profiles, IBM Boston and Quantinuum H2, shows fingerprints exhibit channel-specific structure and yield interpretable heatmaps. We observed systematic cross-platform discrepancies under matched noise configurations, quantified by large Frobenius distances at a fraction of full tomography cost. On 69 MQTBench programs, larger fingerprint differences correlate with output distributions divergences, highlighting threats for testing and cross-platform debugging tasks."

# Summary. An optional shortened abstract.
summary: ""

tags: [Quantum Software Engineering, Noise Models, Cross-Platform Validation]
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
