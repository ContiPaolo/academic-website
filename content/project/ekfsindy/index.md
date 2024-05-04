---
title: Data-driven digital twin: coupling data assimilation with system identification
tags:
  - Deep Learning
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: code
    url: https://github.com/ContiPaolo/EKF-SINDy
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Observed data from a dynamic system can be assimilated into a predictive model by means of Kalman filters. Nonlinear extensions of the Kalman filter, such as the Extended Kalman Filter (EKF), are required to enable the joint estimation of (possibly nonlinear) system dynamics and of input parameters. To construct the evolution model used in the prediction phase of the EKF, we propose to rely on the Sparse Identification of Nonlinear Dynamics (SINDy). The numerical integration of a SINDy model leads to great computational savings compared to alternate strategies based on, e.g., finite elements. Indeed, SINDy allows for the immediate definition of the Jacobian matrices required by the EKF to identify system dynamics and properties, a derivation that is usually extremely involved with physical models. As a result, combining the EKF with SINDy provides a computationally efficient, easy-to-apply approach for the identification of nonlinear systems, capable of robust operation even outside the range of training of SINDy. To demonstrate the potential of the approach, we address the identification of a linear non-autonomous system consisting of a shear building model excited by real seismograms, and the identification of a partially observed nonlinear system. The challenge arising from applying SINDy when the system state is not accessible has been relieved by means of time-delay embedding. The great accuracy and the small uncertainty associated with the state identification, where the state has been augmented to include system properties, underscores the great potential of the proposed strategy, paving the way for the development of predictive digital twins in different fields.

Contributors: Luca Rosafalco, Paolo Conti.
