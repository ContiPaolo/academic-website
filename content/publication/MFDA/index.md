---
title: "Multi-Fidelity Delayed Acceptance: hierarchical MCMC sampling for Bayesian inverse problems combining multiple solvers through deep neural networks"
authors:
- Filippo Zacchei
- admin
- Attilio Frangi
- Andrea Manzoni

date: "2025-10-10T00:00:00Z"
doi: "https://doi.org/10.48550/arXiv.2512.16430"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-10-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv"
publication_short: ""

abstract: Inverse uncertainty quantification (UQ) tasks such as parameter estimation are computationally demanding whenever dealing with physics-based models, and typically require repeated evaluations of complex numerical solvers. When partial differential equations are involved, full-order models such as those based on the Finite Element Method can make traditional sampling approaches like Markov Chain Monte Carlo (MCMC) computationally infeasible. Although data-driven surrogate models may help reduce evaluation costs, their utility is often limited by the expense of generating high-fidelity data. In contrast, low-fidelity data can be produced more efficiently, although relying on them alone may degrade the accuracy of the inverse UQ solution. To address these challenges, we propose a Multi-Fidelity Delayed Acceptance scheme for Bayesian inverse problems. Extending the Multi-Level Delayed Acceptance framework, the method introduces multi-fidelity neural networks that combine the predictions of solvers of varying fidelity, with high fidelity evaluations restricted to an offline training stage. During the online phase, likelihood evaluations are obtained by evaluating the coarse solvers and passing their outputs to the trained neural networks, thereby avoiding additional high-fidelity simulations. This construction allows heterogeneous coarse solvers to be incorporated consistently within the hierarchy, providing greater flexibility than standard Multi-Level Delayed Acceptance. The proposed approach improves the approximation accuracy of the low fidelity solvers, leading to longer sub-chain lengths, better mixing, and accelerated posterior inference. The effectiveness of the strategy is demonstrated on two benchmark inverse problems involving (i) steady isotropic groundwater flow, (ii) an unsteady reaction-diffusion system, for which substantial computational savings are obtained.


# Summary. An optional shortened abstract.
#summary: High-fidelity numerical simulations of partial differential equations (PDEs) given a restricted computational budget can significantly limit the number of parameter configurations considered and/or time window eval- uated for modeling a given system. Multi-fidelity surrogate modeling aims to leverage less accurate, lower- fidelity models that are computationally inexpensive in order to enhance predictive accuracy when high- fidelity data are limited or scarce. However, low-fidelity models, while often displaying important qualitative spatio-temporal features, fail to accurately capture the onset of instability and critical transients observed in the high-fidelity models, making them impractical as surrogate models. To address this shortcoming, we present a new data-driven strategy that combines dimensionality reduction with multi-fidelity neural network surrogates. The key idea is to generate a spatial basis by applying the classical proper orthogonal decom- position (POD) to high-fidelity solution snapshots, and approximate the dynamics of the reduced states - time-parameter-dependent expansion coefficients of the POD basis - using a multi-fidelity long-short term memory (LSTM) network. By mapping low-fidelity reduced states to their high-fidelity counterpart, the proposed reduced-order surrogate model enables the efficient recovery of full solution fields over time and parameter variations in a non-intrusive manner. The generality and robustness of this method is demon- strated by a collection of parametrized, time-dependent PDE problems where the low-fidelity model can be defined by coarser meshes and/or time stepping, as well as by misspecified physical features. Importantly, the onset of instabilities and transients are well captured by this surrogate modeling technique.

#tags:
#- Source Themes
featured: false

url_pdf: "https://arxiv.org/abs/2512.16430"
url_code: "https://github.com/filippozacchei/MFDA"
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
projects: [multifidelity]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: []
---
