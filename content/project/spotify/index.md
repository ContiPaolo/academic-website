---
title: What do you need to climb the charts?
summary: Analysis of a Spotify dataset.
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
    url: https://github.com/ContiPaolo/Spotify_DataAnalysis
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Today, Spotify is undoubtedly one of the most popular and widely used music platforms.
music platforms. More than 40 million tracks by over 2 million artists are available, but only a few thousand are popular with users. So these questions come naturally: what are the common properties of popular songs? What does an artist need in order for their song to climb the charts?
The aim of our project is to try and understand what lies behind a song's popularity, and whether it can be predicted on the basis of song characteristics. To do this, it was fundamental to try and divide songs into groups, according to musical genre, so some grouping was necessary by clustering through unsupervised classification.
As the project progressed, we realized that the musical characteristics of songs alone may not be enough to fully describe them.
In fact, it's much easier for your song to become a worldwide hit if you're Rihanna or Eminem, rather than a street artist! We have therefore added a new variable to our data set, which takes into account the artist's previous popularity. Next, we'll build a linear model to predict the popularity of a given song.
Do users prefer sad or happy music? Energetic or calm music? In this project, we try to answer the questions that guided our analysis.

Contributors: Paolo Conti, Najwa Moursli, Federica Mattina and Nicolò Bonaldi.
