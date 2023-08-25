---
title: "Reduced order modeling of parametrized systems through autoencoders and SINDy approach: continuation of periodic solutions"
authors:
- admin
- Giorgio Gobat
- Stefania Fresca
- Andrea Manzoni
- Attilio Frangi

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-04-15T00:00:00Z"
doi: "https://doi.org/10.1016/j.cma.2023.116072"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Computer Methods in Applied Mechanics and Engineering*"
publication_short: "CMAME"

abstract: Highly accurate simulations of complex phenomena governed by partial differential equations (PDEs) typically require intrusive methods and entail expensive computational costs, which might become prohibitive when approximating steady-state solutions of PDEs for multiple combinations of control parameters and initial conditions. Therefore, constructing efficient reduced order models (ROMs) that enable accurate but fast predictions, while retaining the dynamical characteristics of the physical phenomenon as parameters vary, is of paramount importance. In this work, a data-driven, non-intrusive framework which combines ROM construction with reduced dynamics identification, is presented. Starting from a limited amount of full order solutions, the proposed approach leverages autoencoder neural networks with parametric sparse identification of nonlinear dynamics (SINDy) to construct a low-dimensional dynamical model. This model can be queried to efficiently compute full-time solutions at new parameter instances, as well as directly fed to continuation algorithms. These aim at tracking the evolution of periodic steady-state responses as functions of system parameters, avoiding the computation of the transient phase, and allowing to detect instabilities and bifurcations. Featuring an explicit and parametrized modeling of the reduced dynamics, the proposed data-driven framework presents remarkable capabilities to generalize with respect to both time and parameters. Applications to structural mechanics and fluid dynamics problems illustrate the effectiveness and accuracy of the proposed method.

# Summary. An optional shortened abstract.
summary: Highly accurate simulations of complex phenomena governed by partial differential equations (PDEs) typically require intrusive methods and entail expensive computational costs, which might become prohibitive when approximating steady-state solutions of PDEs for multiple combinations of control parameters and initial conditions. Therefore, constructing efficient reduced order models (ROMs) that enable accurate but fast predictions, while retaining the dynamical characteristics of the physical phenomenon as parameters vary, is of paramount importance. In this work, a data-driven, non-intrusive framework which combines ROM construction with reduced dynamics identification, is presented. Starting from a limited amount of full order solutions, the proposed approach leverages autoencoder neural networks with parametric sparse identification of nonlinear dynamics (SINDy) to construct a low-dimensional dynamical model. This model can be queried to efficiently compute full-time solutions at new parameter instances, as well as directly fed to continuation algorithms. These aim at tracking the evolution of periodic steady-state responses as functions of system parameters, avoiding the computation of the transient phase, and allowing to detect instabilities and bifurcations. Featuring an explicit and parametrized modeling of the reduced dynamics, the proposed data-driven framework presents remarkable capabilities to generalize with respect to both time and parameters. Applications to structural mechanics and fluid dynamics problems illustrate the effectiveness and accuracy of the proposed method.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/pdf/2211.06786.pdf'
url_code: 'https://www.sciencedirect.com/science/article/pii/S0045782523001962?dgcid=author'
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
