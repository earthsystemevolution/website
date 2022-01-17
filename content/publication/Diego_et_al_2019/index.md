+++
title = "Transfer entropy computation using the Perron-Frobenius operator"
date = 2019-04-19T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
#authors = ["David Diego", "Kristian A. Haaga", "Bjarte Hannisdal"]
authors = ["Diego D", "Haaga KA", "Hannisdal B"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Preprint / Working Paper
# 4 = Report
# 5 = Book
# 6 = Book section
# 7 = Thesis
# 8 = Patent
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*Physical Review E* 99: 042212"
publication_short = "*Phys Rev E*  99: 042212"

# Abstract.
abstract = "We propose a method for computing the transfer entropy between time series using Ulam’s approximation of the Perron-Frobenius (transfer) operator associated with the map generating the dynamics. Our method differs from standard transfer entropy estimators in that the invariant measure is estimated not directly from the data points but from the invariant distribution of the transfer operator approximated from the data points. For sparse time series and low embedding dimension, the transfer operator is approximated using a triangulation of the attractor, whereas for data-rich time series or higher embedding dimension we use a faster grid approach. We compare the performance of our methods with existing estimators such as the *k* nearest neighbors method and kernel density estimation method, using coupled instances of well known chaotic systems: coupled logistic maps and a coupled Rössler-Lorenz system. We find that our estimators are robust against moderate levels of noise. For sparse time series with less than a hundred observations and low embedding dimension, our triangulation estimator shows improved ability to detect coupling directionality, relative to standard transfer entropy estimators."

# Summary. An optional shortened abstract.
summary = "We compute transfer entropy by estimating the invariant measure from the invariant distribution of the transfer operator approximated from time series. We use two methods for approximating the transfer operator, and find that our methods are robust to noise and show promising performance relative to other transfer entropy estimators."

# Digital Object Identifier (DOI)
doi = "10.1103/PhysRevE.99.042212"

# Is this a featured publication? (true/false)
featured = true

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Highlights"]

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = "https://journals.aps.org/pre/pdf/10.1103/PhysRevE.99.042212"
url_code = "https://github.com/kahaaga/CausalityTools.jl"
#url_dataset = ""
#url_project = ""
#url_slides = ""
#url_video = ""
#url_poster = ""
#url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
links = [{name = "arXiv", url = "https://arxiv.org/pdf/1811.01677.pdf"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++

