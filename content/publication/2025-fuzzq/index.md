---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Shaking Up Quantum Simulators with Fuzzing and Rigour"
authors:
  - Vasileios Klimis
  - Avner Bensoussan
  - Elena Chachkarova
  - Karine Even-Mendoza
  - admin
  - Connor Lenihan

date: 2025-09-10
doi: "10.1145/3763100"

# Schedule page publish date (NOT publication's date).
publishDate: 2025-06-18

# Publication type: paper-conference, article-journal, article-newspaper, book, chapter, masters-thesis, preprint, report, thesis, webpage (from CSL standard)
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "In the *ACM SIGPLAN International Conference on Object-Oriented Programming Systems, Languages, and Applications*"
publication_short: "In *OOPSLA 2025*"

abstract: "Quantum computing platforms rely on simulators for modelling circuit behaviour prior to hardware execution, where inconsistencies can lead to costly errors. While existing formal validation methods typically target specific compiler components to manage state explosion, they often miss critical bugs. Meanwhile, conventional testing lacks systematic exploration of corner cases and realistic execution scenarios, resulting in both false positives and negatives. We present FuzzQ, a novel framework that bridges this gap by combining formal methods with structured test generation and fuzzing for quantum simulators. Our approach employs differential benchmarking complemented by mutation testing and invariant checking. At its core, FuzzQ utilises our Alloy-based formal model of QASM 3.0, which encodes the semantics of quantum circuits to enable automated analysis and to generate structurally diverse, constraint-guided quantum circuits with guaranteed properties. We introduce several test oracles to assess both Alloy’s modelling of QASM 3.0 and simulator correctness, including invariant-based checks, statistical distribution tests, and a novel cross-simulator unitary consistency check that verifies functional equivalence modulo global phase, revealing discrepancies that standard statevector comparisons fail to detect in cross-platform differential testing. We evaluate FuzzQ on both Qiskit and Cirq, demonstrating its platform-agnostic effectiveness. By executing over 800,000 quantum circuits to completion, we assess throughput, code and circuit coverage, and simulator performance metrics, including sensitivity, correctness, and memory overhead. Our analysis revealed eight simulator bugs, six previously undocumented. We also outline a path for extending the framework to support mixed-state simulations under realistic noise models."

# Summary. An optional shortened abstract.
summary: ""

tags: [Quantum Software Engineering, Formal Methods, Alloy, Fuzzing, Differential Testing, Model-Based Testing, Quantum Circuit Simulation, Alloy Analyzer]
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
