---
title: Oral Presentation at KDD 2022

event: KDD22 Conference
event_url: https://kdd.org/kdd2022/paperRT.html

location: Washington DC Convention Center
address:
  street: 801 Allen Y. Lew Place NW 
  city: Washington
  region: DC
  postcode: '20001'
  country: United States

summary: Present the paper "Quantifying and Reducing Registration Uncertainty of Spatial Vector Labels on Earth Imagery"
abstract: 'Given raster imagery features and imperfect vector training labels with registration uncertainty, this paper studies a deep learning framework that can quantify and reduce the registration uncertainty of training labels as well as train neural network parameters simultaneously. The problem is important in broad applications such as streamline classification on Earth imagery or tissue segmentation on medical imagery, whereby annotating precise vector labels is expensive and time-consuming. However, the problem is challenging due to the gap between the vector representation of class labels and the raster representation of image features and the need for training neural networks with uncertain label locations. Existing research on uncertain training labels often focuses on uncertainty in label class semantics or characterizes label registration uncertainty at the pixel level (not contiguous vectors). To fill the gap, this paper proposes a novel learning framework that explicitly quantifies vector labels registration uncertainty. We propose a registration-uncertainty-aware loss function and design an iterative uncertainty reduction algorithm by re-estimating the posterior of true vector label locations distribution based on a Gaussian process. Evaluations on real-world datasets in National Hydrography Dataset refinement show that the proposed approach significantly outperforms several baselines in the registration uncertainty estimations performance and classification performance.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2022-08-16T13:00:00Z'
date_end: '2020-08-16T14:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2022-08-16T00:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit:  Zhe Jiang'
  focal_point: Right

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - example
---

{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Wowchemy's [_Slides_](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page.
