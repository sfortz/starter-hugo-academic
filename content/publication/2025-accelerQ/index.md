---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "AccelerQ: Accelerating Quantum Eigensolvers With Machine Learning on Quantum Simulators"
authors:
  - Avner Bensoussan
  - Elena Chachkarova
  - Karine Even-Mendoza
  - admin
  - Connor Lenihan
date: 2025-10-12
doi: #"10.1145/3472674.3473980"

# Schedule page publish date (NOT publication's date).
publishDate: 2025-06-18

# Publication type: paper-conference, article-journal, article-newspaper, book, chapter, masters-thesis, preprint, report, thesis, webpage (from CSL standard)
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "In the *ACM SIGPLAN International Conference on Object-Oriented Programming Systems, Languages, and Applications*"
publication_short: "In *OOPSLA 2025*"

abstract: "We present AccelerQ, a framework for automatically tuning quantum eigensolver (QE) implementations–these are quantum programs implementing a specific QE algorithm–using machine learning and search-based optimisation. Rather than redesigning quantum algorithms or optimising the implementation of an already existing algorithm, AccelerQ treats QE implementations as black-box programs and learns to optimise their hyperparameters to improve accuracy and efficiency. <br /><br /> Our approach leverages two key insights: (1) training on data extracted from smaller and simpler QE implementations’ inputs, and (2) training a program-specific ML model. To further enhance our approach, we incorporate search-based techniques and genetic algorithms alongside machine learning models to efficiently explore the hyperparameter space of QE implementations and avoid local minima.  <br /><br /> To evaluate AccelerQ, we applied it to the Quantum Eigensolver as a use case using two fundamentally different quantum implementations: ADAPT-QSCI and QCELS. For each, we trained a lightweight XGBoost Python regressor model using data extracted classically from systems of up to 16 qubits. We deployed the model to optimise hyperparameters for executions on larger systems–20-, 24-, and 28-qubit Hamiltonians, where direct classical simulation becomes impractical. <br /><br /> For ADAPT-QSCI, we observed a reduction in error from 5.48% to 5.3% with only the ML model and further to 5.05% using genetic algorithms. For QCELS, ML reduced the error from 7.5% to 6.5%, with no additional gain from genetic algorithm use. Our results highlight the potential of machine learning and optimisation techniques for quantum programs and suggest promising directions for integrating software engineering methods into quantum software stacks. Nonetheless, due to inconclusive results with some of the Hamiltonian systems of 20- and 24-qubit systems, we suggest further examination of the training data based on Hamiltonian characteristics."

# Summary. An optional shortened abstract.
summary: ""

tags: [Quantum Computing, Quantum Program Analysis, Optimisation, Machine Learning, Search-based Software Engineering, Genetic Algorithms]
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
