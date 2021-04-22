+++
title = "Sage: Practical & Scalable ML-Driven Performance Debugging in Microservices"
date = 2021-04-13
publishdate = 2020-11-20

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["yu_gan", "Mingyu Liang", "Sundar Dev", "David Lo", "Christina Delimitrou"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "To appear in 26th ACM International Conference on Architectural Support for Programming Languages and Operating Systems"
publication_short = "[ASPLOS'21](https://asplos-conference.org/)"

# Abstract.
abstract = "Cloud applications are increasingly shifting from large monolithic services to complex graphs of loosely-coupled microservices. Despite the advantages of modularity and elasticity microservices offer, they also complicate cluster management and performance debugging, as dependencies between tiers introduce backpressure and cascading QoS violations. Prior work on performance debugging for cloud services either relies on empirical techniques, or uses supervised learning to diagnose the root causes of performance issues, which requires significant application instrumentation, and is difficult to deploy in practice. \nWe present Sage, a machine learning-driven root cause analysis system for interactive cloud microservices that focuses on practicality and scalability. Sage leverages unsupervised ML models to circumvent the overhead of trace labeling, captures the impact of dependencies between microservices to determine the root cause of unpredictable performance online, and applies corrective actions to recover a cloud service’s QoS. In experiments on both dedicated local clusters and large clusters on Google Compute Engine we show that Sage consistently achieves over 93% accuracy in correctly identifying the root cause of QoS violations, and improves performance predictability."


# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = "10.1145/3445814.3446700"

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
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = "2021.asplos.sage.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "2021.asplos.sage.slides.pdf"
url_video = "https://youtu.be/5S1j9ZAEDuk"
url_poster = ""
url_source = ""
url_cite = "cite.bib"


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
  focal_point = ""
+++
