---
title: "Soft sensor design using hierarchical multi-fidelity modeling with bayesian optimization for input variable selection"
authors:
- Johannes Lips
- Hendrik Lens
- admin

date: "2025-01-01T00:00:00Z"
doi: "https://doi.org/10.1016/j.ifacol.2025.07.135"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Soft sensors, or inferential sensors, are crucial in quality and process control systems because they allow for e!cient, online estimation of essential quantities that are otherwise di!cult or expensive to measure directly. In many applications, it is common to use cost-e”ective measurement equipment, o”ering faster data collection than high-fidelity measurements, albeit at the price of reduced accuracy. These low-fidelity data can provide useful information to enhance the estimation of output quantities of interest, thereby facilitating the design of inferential control systems. In this work, we introduce an innovative approach to soft sensing by employing hierarchical, multi-fidelity surrogate models as soft sensors, integrated with Bayesian optimization for input variable selection. Our method creates a parsimonious model by identifying and organizing relevant inputs into a fidelity hierarchy, which enables a multi-fidelity neural network to sequentially refine estimations by extracting crucial information progressively. First, we showcase the e”ectiveness of the proposed framework on a numerical benchmark, then we use our method to create a surrogate model as soft sensor for accurately determining the atmospheric particulate matter concentration (PM2.5) using real data collected from low-cost sensors.


# Summary. An optional shortened abstract.
#summary: High-fidelity numerical simulations of partial differential equations (PDEs) given a restricted computational budget can significantly limit the number of parameter configurations considered and/or time window eval- uated for modeling a given system. Multi-fidelity surrogate modeling aims to leverage less accurate, lower- fidelity models that are computationally inexpensive in order to enhance predictive accuracy when high- fidelity data are limited or scarce. However, low-fidelity models, while often displaying important qualitative spatio-temporal features, fail to accurately capture the onset of instability and critical transients observed in the high-fidelity models, making them impractical as surrogate models. To address this shortcoming, we present a new data-driven strategy that combines dimensionality reduction with multi-fidelity neural network surrogates. The key idea is to generate a spatial basis by applying the classical proper orthogonal decom- position (POD) to high-fidelity solution snapshots, and approximate the dynamics of the reduced states - time-parameter-dependent expansion coefficients of the POD basis - using a multi-fidelity long-short term memory (LSTM) network. By mapping low-fidelity reduced states to their high-fidelity counterpart, the proposed reduced-order surrogate model enables the efficient recovery of full solution fields over time and parameter variations in a non-intrusive manner. The generality and robustness of this method is demon- strated by a collection of parametrized, time-dependent PDE problems where the low-fidelity model can be defined by coarser meshes and/or time stepping, as well as by misspecified physical features. Importantly, the onset of instabilities and transients are well captured by this surrogate modeling technique.

#tags:
#- Source Themes
featured: false

url_pdf: "https://www.sciencedirect.com/science/article/pii/S2405896325004951"
url_code: "https://github.com/ContiPaolo/MultiFidelityBO_SoftSensor"
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
projects: [progressive]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: []
---
