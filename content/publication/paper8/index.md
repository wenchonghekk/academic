---
title: "Semi-Supervised Learning With the EM Algorithm: A Comparative Study Between Unstructured and Structured Prediction"
authors:
- admin
- Zhe Jiang
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2022-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Knowledge and Data Engineering*
publication_short: In *IEEE TKDE 2022* 


abstract: Semi-supervised learning aims to learn prediction models from both labeled and unlabeled samples. There has been extensive research in this area. Among existing work, generative mixture models with Expectation-Maximization (EM) is a popular method due to clear statistical properties. However, existing literature on EM-based semi-supervised learning largely focuses on unstructured prediction, assuming that samples are independent and identically distributed. Studies on EM-based semi-supervised approach in structured prediction is limited. This article aims to fill the gap through a comparative study between unstructured and structured methods in EM-based semi-supervised learning. Specifically, we compare their theoretical properties and find that both methods can be considered as a generalization of self-training with soft class assignment of unlabeled samples, but the structured method additionally considers structural constraint in soft class assignment. We conducted a case study on real-world flood mapping datasets to compare the two methods. Results show that structured EM is more robust to class confusion caused by noise and obstacles in features in the context of the flood mapping application.




# Summary. An optional shortened abstract.
summary: we conduct a comparative study between unstructured and structured methods in EM-based semi-supervised learning.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9177326'
url_code: 'https://github.com/ZelinXu2000/SKI-HL'
url_dataset: 'https://github.com/ZelinXu2000/SKI-HL'
url_poster: 'https://github.com/ZelinXu2000/SKI-HL'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

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
slides: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/). -->
