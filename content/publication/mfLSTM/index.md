---
title: "Multi-fidelity surrogate modeling using long short-term memory networks"
authors:
- admin
- Mengwu Guo
- Andrea Manzoni
- Jan S. Hesthaven

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-02-01T00:00:00Z"
doi: "https://doi.org/10.1016/j.cma.2022.115811"

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

abstract: When evaluating quantities of interest that depend on the solutions to differential equations, we inevitably face the trade-off between accuracy and efficiency. Especially for parametrized, time-dependent problems in engineering computations, it is often the case that acceptable computational budgets limit the availability of high-fidelity, accurate simulation data. Multi-fidelity surrogate modeling has emerged as an effective strategy to overcome this difficulty. Its key idea is to leverage many low-fidelity simulation data, less accurate but much faster to compute, to improve the approximations with limited high-fidelity data. In this work, we introduce a novel data-driven framework of multi-fidelity surrogate modeling for parametrized, time-dependent problems using long short-term memory (LSTM) networks, to enhance output predictions both for unseen parameter values and forward in time simultaneously — a task known to be particularly challenging for data-driven models. We demonstrate the wide applicability of the proposed approaches in a variety of engineering problems with high- and low-fidelity data generated through fine versus coarse meshes, small versus large time steps, or finite element full order versus deep learning reduced-order models. Numerical results show that the proposed multi-fidelity LSTM networks not only improve single-fidelity regression significantly, but also outperform the multi-fidelity models based on feed-forward neural networks.

# Summary. An optional shortened abstract.
summary: When evaluating quantities of interest that depend on the solutions to differential equations, we inevitably face the trade-off between accuracy and efficiency. Especially for parametrized, time-dependent problems in engineering computations, it is often the case that acceptable computational budgets limit the availability of high-fidelity, accurate simulation data. Multi-fidelity surrogate modeling has emerged as an effective strategy to overcome this difficulty. Its key idea is to leverage many low-fidelity simulation data, less accurate but much faster to compute, to improve the approximations with limited high-fidelity data. In this work, we introduce a novel data-driven framework of multi-fidelity surrogate modeling for parametrized, time-dependent problems using long short-term memory (LSTM) networks, to enhance output predictions both for unseen parameter values and forward in time simultaneously — a task known to be particularly challenging for data-driven models. We demonstrate the wide applicability of the proposed approaches in a variety of engineering problems with high- and low-fidelity data generated through fine versus coarse meshes, small versus large time steps, or finite element full order versus deep learning reduced-order models. Numerical results show that the proposed multi-fidelity LSTM networks not only improve single-fidelity regression significantly, but also outperform the multi-fidelity models based on feed-forward neural networks.


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
