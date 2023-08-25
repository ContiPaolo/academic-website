---
title: "Multi-fidelity regression using artificial neural networks: Efficient approximation of parameter-dependent output quantities"
authors:
- Mengwu Guo
- Andrea Manzoni
- Maurice Amendt
- admin
- Jan S. Hesthaven

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2022-02-01T00:00:00Z"
doi: "https://doi.org/10.1016/j.cma.2021.114378"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Computer Methods in Applied Mechanics and Engineering*(1)"
publication_short: "CMAME"

abstract: Highly accurate numerical or physical experiments are often very time-consuming or expensive to obtain. When time or budget restrictions prohibit the generation of additional data, the amount of available samples may be too limited to provide satisfactory model results. Multi-fidelity methods deal with such problems by incorporating information from other sources, which are ideally well-correlated with the high-fidelity data, but can be obtained at a lower cost. By leveraging correlations between different data sets, multi-fidelity methods often yield superior generalization when compared to models based solely on a small amount of high-fidelity data. In the current work, we present the use of artificial neural networks applied to multi-fidelity regression problems. By elaborating a few existing approaches, we propose new neural network architectures for multi-fidelity regression. The introduced models are compared against a traditional multi-fidelity regression scheme — co-kriging. A collection of artificial benchmarks are presented to measure the performance of the analyzed models. The results show that cross-validation in combination with Bayesian optimization leads to neural network models that outperform the co-kriging scheme. Additionally, we show an application of multi-fidelity regression to an engineering problem. The propagation of a pressure wave into an acoustic horn with parametrized shape and frequency is considered, and the index of reflection intensity is approximated using the proposed multi-fidelity models. A finite element, full-order model and a reduced-order model built through the reduced basis method are adopted as the high- and low-fidelity, respectively. It is shown that the multi-fidelity neural networks return outputs that achieve a comparable accuracy to those from the expensive, full-order model, using only very few full-order evaluations combined with a larger amount of inaccurate but cheap evaluations of the reduced order model.

# Summary. An optional shortened abstract.
summary: Highly accurate numerical or physical experiments are often very time-consuming or expensive to obtain. When time or budget restrictions prohibit the generation of additional data, the amount of available samples may be too limited to provide satisfactory model results. Multi-fidelity methods deal with such problems by incorporating information from other sources, which are ideally well-correlated with the high-fidelity data, but can be obtained at a lower cost. By leveraging correlations between different data sets, multi-fidelity methods often yield superior generalization when compared to models based solely on a small amount of high-fidelity data. In the current work, we present the use of artificial neural networks applied to multi-fidelity regression problems. By elaborating a few existing approaches, we propose new neural network architectures for multi-fidelity regression. The introduced models are compared against a traditional multi-fidelity regression scheme — co-kriging. A collection of artificial benchmarks are presented to measure the performance of the analyzed models. The results show that cross-validation in combination with Bayesian optimization leads to neural network models that outperform the co-kriging scheme. Additionally, we show an application of multi-fidelity regression to an engineering problem. The propagation of a pressure wave into an acoustic horn with parametrized shape and frequency is considered, and the index of reflection intensity is approximated using the proposed multi-fidelity models. A finite element, full-order model and a reduced-order model built through the reduced basis method are adopted as the high- and low-fidelity, respectively. It is shown that the multi-fidelity neural networks return outputs that achieve a comparable accuracy to those from the expensive, full-order model, using only very few full-order evaluations combined with a larger amount of inaccurate but cheap evaluations of the reduced order model.


tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/abs/2102.13403
url_code: 'https://www.sciencedirect.com/science/article/pii/S0045782521006411'
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
