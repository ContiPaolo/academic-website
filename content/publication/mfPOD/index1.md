---
title: "Deep Learning-based surrogate models for parametrized PDEs: handling geometric variability through graph neural networks"
authors:
- Nicola Rares Franco
- admin
- Filippo Tombari
- Andrea Manzoni
date: "2023-08-03T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv preprint arXiv:2308.01602"
publication_short: ""

abstract: Mesh-based simulations play a key role when modeling complex physical systems that, in many disciplines across science and engineering, require the solution of parametrized time-dependent non- linear partial differential equations (PDEs). In this context, full order models (FOMs), such as those relying on the finite element method, can reach high levels of accuracy, however often yielding intensive simulations to run. For this reason, surrogate models are developed to replace computationally expensive solvers with more efficient ones, which can strike favorable trade-offs between accuracy and efficiency. This work explores the potential usage of graph neural networks (GNNs) for the simulation of time-dependent PDEs in the presence of geometrical variability. In particular, we propose a systematic strategy to build surrogate models based on a data-driven time-stepping scheme where a GNN architecture is used to efficiently evolve the system. With respect to the majority of surrogate models, the proposed approach stands out for its ability of tackling problems with parameter dependent spatial domains, while simultaneously generalizing to different geometries and mesh resolutions. We assess the effectiveness of the proposed approach through a series of numerical experiments, involving both two- and three-dimensional problems, showing that GNNs can provide a valid alternative to traditional surrogate models in terms of computational efficiency and generalization to new scenarios. We also assess, from a numerical standpoint, the importance of using GNNs, rather than classical dense deep neural networks, for the proposed framework.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
#- Source Themes
featured: false

url_pdf: https://arxiv.org/pdf/2308.01602.pdf
url_code:
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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
slides: []
---
