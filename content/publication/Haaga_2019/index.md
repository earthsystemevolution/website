+++
title = "UncertainData.jl: a Julia package for working with measurements and datasets with uncertainties"
date = 2019-11-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Haaga KA"]

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
publication = "*Journal of Open Source Software* 8: 11520"
publication_short = "*JOSS*  4: 1666"

# Abstract.
abstract = "UncertainData.jl provides an interface to represent data with associated uncertainties for the Julia programming language (Bezanson, Edelman, Karpinski, & Shah, 2017). Unlike Measurements.jl (Giordano, 2016), which deals with exact error propagation of normally distributed values, UncertainData.jl uses a resampling approach to deal with uncertainties in calculations. This allows working with and combining any type of uncertain value for which a resampling method can be defined. Examples of currently supported uncertain values are:theoretical distributions, e.g., those supported by Distributions.jl (Besançon et al., 2019; Linet al., 2019); values whose states are represented by a finite set of values with weighted probabilities; values represented by empirical distributions; and more. The package simplifies resampling from uncertain datasets whose data points potentially have different kinds of uncertainties, both in data values and potential index values (e.g., time or space). The user may resample using a set of pre-defined constraints, truncating the supports of the distributions furnishing the uncertain datasets, combined with interpolation on pre-defined grids. Methods for sequential resampling of ordered datasets that have indices with uncertainties are also provided. Using Julia’s multiple dispatch, UncertainData.jl extends most elementary mathematical operations, hypothesis tests from HypothesisTests.jl, and various methods from the StatsBase.jl package for uncertain values and uncertain datasets.  Additional statistical algorithms in other packages are trivially adapted to handle uncertain values and datasets from UncertainData.jl by using multiple dispatch and the provided resampling framework. UncertainData.jl was originally designed to form the backbone of the uncertainty handling in the CausalityTools.jl package, with the aim of quantifying the sensitivity of statistical timeseries causality detection algorithms. Recently, the package has also been used in paleoclimate research (Vasskog et al., 2019)."

# Summary. An optional shortened abstract.
summary = "UncertainData.jl provides an interface to represent data with associated uncertainties for the Julia programming language, using a resampling approach to deal with uncertainties in calculations."

# Digital Object Identifier (DOI)
doi = "10.21105/joss.01666"

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

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
url_pdf = "https://joss.theoj.org/papers/10.21105/joss.01666"
url_code = "https://github.com/kahaaga/UncertainData.jl"
#url_dataset = ""
#url_project = ""
#url_slides = ""
#url_video = ""
#url_poster = ""
#url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{name = "Custom Link", url = "http://example.org"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++

<!--
{{% alert note %}}
Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
{{% /alert %}}
-->
