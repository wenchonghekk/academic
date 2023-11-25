---
title: "Weakly Supervised Spatial Deep Learning for Earth Image Segmentation Based on Imperfect Polyline Labels"
authors:
- Zhe Jiang
- admin
- Marcus Kriby
- Arpan Man Sainju
- Shaowen Wang
- Lawrence V. Stanislawski
- Ethan J. Shavers
- E. Lynn Usery
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2022-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *ACM Transactions on Intelligent Systems and Technology*
publication_short: In *ACM TIST 2022* 


abstract: In recent years, deep learning has achieved tremendous success in image segmentation for computer vision applications. The performance of these models heavily relies on the availability of large-scale high-quality training labels (e.g., PASCAL VOC 2012). Unfortunately, such large-scale high-quality training data are often unavailable in many real-world spatial or spatiotemporal problems in earth science and remote sensing (e.g., mapping the nationwide river streams for water resource management). Although extensive efforts have been made to reduce the reliance on labeled data (e.g., semi-supervised or unsupervised learning, few-shot learning), the complex nature of geographic data such as spatial heterogeneity still requires sufficient training labels when transferring a pre-trained model from one region to another. On the other hand, it is often much easier to collect lower-quality training labels with imperfect alignment with earth imagery pixels (e.g., through interpreting coarse imagery by non-expert volunteers). However, directly training a deep neural network on imperfect labels with geometric annotation errors could significantly impact model performance. Existing research that overcomes imperfect training labels either focuses on errors in label class semantics or characterizes label location errors at the pixel level. These methods do not fully incorporate the geometric properties of label location errors in the vector representation. To fill the gap, this article proposes a weakly supervised learning framework to simultaneously update deep learning model parameters and infer hidden true vector label locations. Specifically, we model label location errors in the vector representation to partially reserve geometric properties (e.g., spatial contiguity within line segments). Evaluations on real-world datasets in the National Hydrography Dataset (NHD) refinement application illustrate that the proposed framework outperforms baseline methods in classification accuracy.


# Summary. An optional shortened abstract.
summary: We proposes a weakly supervised learning framework to simultaneously update deep learning model parameters and infer hidden true vector label locations.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://dl.acm.org/doi/full/10.1145/3480970'
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
