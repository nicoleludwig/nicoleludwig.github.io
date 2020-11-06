---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Evaluating Ensemble Post-Processing for Wind Power Forecasts
subtitle: ''
summary: ''
authors:
- Kaleb Phipps
- Sebastian Lerch
- Maria Andersson
- Ralf Mikut
- Veit Hagenmeyer
- Nicole Ludwig
tags: []
categories: []
date: 29.09.2020-01-01
lastmod: 2020-11-06T11:25:41+01:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-11-06T10:25:40.216001Z'
publication_types:
- '0'
abstract: 'Capturing the uncertainty in probabilistic wind power forecasts is challenging,
  especially when uncertain input variables, such as the weather play a role. Since
  ensemble weather predictions aim to capture this uncertainty in the weather system
  accurately, they can be used to propagate this uncertainty through to subsequent
  wind power forecasting models. However, as weather ensemble systems are known to
  be biased and underdispersed, meteorologists post-process the ensembles. This post-processing
  can successfully correct the biases in the weather variables but has not been evaluated
  thoroughly in the context of subsequent forecasts, such as wind power generation.  The
  present paper evaluates multiple strategies for applying ensemble post-processing
  to probabilistic wind power forecasts. We use Ensemble Model Output Statistics (EMOS)
  as the post-processing method and evaluate four possible strategies: only using
  the raw ensembles without post-processing, a one-step strategy where only the weather
  ensembles are post-processed, a one-step strategy where we only post-process the
  power ensembles, and a two-step strategy where we post-process both the weather
  and power ensembles. Results show that post-processing improves the probabilistic
  forecasting accuracy and that the post-processing of the final power ensemble forecast
  is the crucial step.'
publication: ''
url_pdf: https://arxiv.org/pdf/2009.14127
---
