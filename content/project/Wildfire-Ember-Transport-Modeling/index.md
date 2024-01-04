---
title: Wildfire Ember Transport Modeling
summary: Large eddy simulation of horizontally homogeneous forest canopy for validation of PALM.
tags:
  - Turbulence
  - Firebrands
  - Embers
  - Wildfires
date: '2023-05-15T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by [Michael Benz](https://unsplash.com/photos/green-plants-with-white-background--IZ2sgQKIhM) on Unsplash
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: ''
url_pdf: 'https://scholarworks.sjsu.edu/etd_theses/5394'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ''
---

# Overview
This project is about the numerical modeling of firebrand showers in wildfire simulations.

- **Problem**: Firebrands can spread wildfire through the ignition of spot fires, yet there is a gap in knowledge on where they will land due to turbulent wind 

- **Solution**: Model high-resolution turbulent boundary layers at various turbulence intensities, and release firebrands in those domains to study the effect of small-scale turbulence 

- **Results**: Novel implementation of firebrand transport model coupled with wildfire simulation WRF-SFIRE for comparison between large-scale and small-scale transport

![Alt text](image.png)