---
title: "Multi-fidelity reduced-order surrogate modeling"
authors:
- admin
- Mengwu Guo
- Andrea Manzoni
- Attilio Frangi
- J. Nathan Kutz
- Steven L. Brunton

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-02-01T00:00:00Z"
doi: 

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract: High-fidelity numerical simulations of partial differential equations (PDEs) given a restricted computational
budget can significantly limit the number of parameter configurations considered and/or time window evaluated
for modeling a given system. Multi-fidelity surrogate modeling aims to leverage less accurate, lowerfidelity
models that are computationally inexpensive in order to enhance predictive accuracy when highfidelity
data are limited or scarce. However, low-fidelity models, while often displaying important qualitative
spatio-temporal features, fail to accurately capture the onset of instability and critical transients observed
in the high-fidelity models, making them impractical as surrogate models. To address this shortcoming, we
present a new data-driven strategy that combines dimensionality reduction with multi-fidelity neural network
surrogates. The key idea is to generate a spatial basis by applying the classical proper orthogonal decomposition
(POD) to high-fidelity solution snapshots, and approximate the dynamics of the reduced states —
time-parameter-dependent expansion coefficients of the POD basis – using a multi-fidelity long-short term
memory (LSTM) network. By mapping low-fidelity reduced states to their high-fidelity counterpart, the
proposed reduced-order surrogate model enables the efficient recovery of full solution fields over time and
parameter variations in a non-intrusive manner. The generality and robustness of this method is demonstrated
by a collection of parametrized, time-dependent PDE problems where the low-fidelity model can be
defined by coarser meshes and/or time stepping, as well as by misspecified physical features. Importantly,
the onset of instabilities and transients are well captured by this surrogate modeling technique.

# Summary. An optional shortened abstract.
summary:


tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/pdf/2208.03115.pdf'
url_code: 'https://www.sciencedirect.com/science/article/abs/pii/S0045782522007678'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
