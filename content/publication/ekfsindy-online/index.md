---
title: "Online learning in bifurcating dynamic systems via SINDy and Kalman filterings"
authors:
- Luca Rosafalco
- admin
- Andrea Manzoni
- Stefano Mariani
- Attilio Frangi

date: "2025-01-01T00:00:00Z"
doi: "https://doi.org/10.48550/arXiv.2411.04842"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Nonlinear Dynamics"
publication_short: ""

abstract: "We propose the use of the Extended Kalman Filter (EKF) for online data assimilation and update of a dynamic model, preliminary identified through the Sparse Identification of Nonlinear Dynamics (SINDy). This data-driven technique may avoid biases due to incorrect modelling assumptions and exploits SINDy to approximate the system dynamics leveraging a predefined library of functions, where active terms are selected and weighted by a sparse set of coefficients. This results in a physically-sound and interpretable dynamic model allowing to reduce epistemic uncertainty often affecting machine learning approaches. Treating the SINDy model coefficients as random variables, we propose to update them while acquiring (possibly noisy) system measurements, thus enabling the online identification of time-varying systems. These changes can stem from, e.g., varying operational conditions or unforeseen events. The EKF performs model adaptation through joint state-parameters estimation, with the Jacobian matrices required to computed the model sensitivity inexpensively evaluated from the SINDy model formulation. The effectiveness of this approach is demonstrated through three case studies: (i) a Lokta-Volterra model in which all parameters simultaneously evolve during the observation period; (ii) a Selkov model where the system undergoes a bifurcation not seen during the SINDy training; (iii) a MEMS arch exhibiting a 1:2 internal resonance. The ability of EKF of recovering inactivated functional terms from the SINDy library, or discarding unnecessary contribution, is also highlighted. Based on the presented applications, this method shows strong promise for handling time-varying nonlinear dynamic systems possibly experiencing bifurcating behaviours."


# Summary. An optional shortened abstract.
#summary: "We propose the use of the Extended Kalman Filter (EKF) for online data assimilation and update of a dynamic model, preliminary identified through the Sparse Identification of Nonlinear Dynamics (SINDy). This data-driven technique may avoid biases due to incorrect modelling assumptions and exploits SINDy to approximate the system dynamics leveraging a predefined library of functions, where active terms are selected and weighted by a sparse set of coefficients. This results in a physically-sound and interpretable dynamic model allowing to reduce epistemic uncertainty often affecting machine learning approaches. Treating the SINDy model coefficients as random variables, we propose to update them while acquiring (possibly noisy) system measurements, thus enabling the online identification of time-varying systems. These changes can stem from, e.g., varying operational conditions or unforeseen events. The EKF performs model adaptation through joint state-parameters estimation, with the Jacobian matrices required to computed the model sensitivity inexpensively evaluated from the SINDy model formulation. The effectiveness of this approach is demonstrated through three case studies: (i) a Lokta-Volterra model in which all parameters simultaneously evolve during the observation period; (ii) a Selkov model where the system undergoes a bifurcation not seen during the SINDy training; (iii) a MEMS arch exhibiting a 1:2 internal resonance. The ability of EKF of recovering inactivated functional terms from the SINDy library, or discarding unnecessary contribution, is also highlighted. Based on the presented applications, this method shows strong promise for handling time-varying nonlinear dynamic systems possibly experiencing bifurcating behaviours."

#tags:
#- Source Themes
featured: false

url_pdf: "https://link.springer.com/article/10.1007/s11071-025-11029-"
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
projects: [ekfsindy]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: []
---
