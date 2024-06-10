---
title: "VENI, VINDy, VICI: a variational reduced-order modeling framework with uncertainty quantification"
authors:
- admin
- Jonas Kneifl
- Andrea Manzoni
- Attilio Frangi
- Steven L. Brunton
- J. Nathan Kutz

date: "2024-06-01T00:00:00Z"
doi: "https://doi.org/10.48550/arXiv.2405.20905"


# Schedule page publish date (NOT publication's date).
publishDate: "2024-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv"
publication_short: ""

abstract: The simulation of many complex phenomena in engineering and science requires solving expensive, high-dimensional systems of partial differential equations (PDEs). To circumvent this, reduced-order models (ROMs) have been developed to speed up computations. However, when governing equations are unknown or partially known, typically ROMs lack interpretability and reliability of the predicted solutions. In this work we present a data-driven, non-intrusive framework for building ROMs where the latent variables and dynamics are identified in an interpretable manner and uncertainty is quantified. Starting from a limited amount of high-dimensional, noisy data the proposed framework constructs an efficient ROM by leveraging variational autoencoders for dimensionality reduction along with a newly introduced, variational version of sparse identification of nonlinear dynamics (SINDy), which we refer to as Variational Identification of Nonlinear Dynamics (VINDy). In detail, the method consists of Variational Encoding of Noisy Inputs (VENI) to identify the distribution of reduced coordinates. Simultaneously, we learn the distribution of the coefficients of a pre-determined set of candidate functions by VINDy. Once trained offline, the identified model can be queried for new parameter instances and new initial conditions to compute the corresponding full-time solutions. The probabilistic setup enables uncertainty quantification as the online testing consists of Variational Inference naturally providing Certainty Intervals (VICI). In this work we showcase the effectiveness of the newly proposed VINDy method in identifying interpretable and accurate dynamical system for the Rössler system with different noise intensities and sources. Then the performance of the overall method - named VENI, VINDy, VICI - is tested on PDE benchmarks including structural mechanics and fluid dynamics.


# Summary. An optional shortened abstract.
#summary: Observed data from a dynamic system can be assimilated into a predictive model by means of Kalman filters. Nonlinear extensions of the Kalman filter, such as the Extended Kalman Filter (EKF), are required to enable the joint estimation of (possibly nonlinear) system dynamics and of input parameters. To construct the evolution model used in the prediction phase of the EKF, we propose to rely on the Sparse Identification of Nonlinear Dynamics (SINDy). The numerical integration of a SINDy model leads to great computational savings compared to alternate strategies based on, e.g., finite elements. Indeed, SINDy allows for the immediate definition of the Jacobian matrices required by the EKF to identify system dynamics and properties, a derivation that is usually extremely involved with physical models. As a result, combining the EKF with SINDy provides a computationally efficient, easy-to-apply approach for the identification of nonlinear systems, capable of robust operation even outside the range of training of SINDy. To demonstrate the potential of the approach, we address the identification of a linear non-autonomous system consisting of a shear building model excited by real seismograms, and the identification of a partially observed nonlinear system. The challenge arising from applying SINDy when the system state is not accessible has been relieved by means of time-delay embedding. The great accuracy and the small uncertainty associated with the state identification, where the state has been augmented to include system properties, underscores the great potential of the proposed strategy, paving the way for the development of predictive digital twins in different fields.

#tags:
#- Source Themes
featured: false

url_pdf: "https://arxiv.org/abs/2404.07536"
url_code: "https://github.com/ContiPaolo/EKF-SINDy"
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
