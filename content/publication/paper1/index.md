---
title: "Spatial Knowledge-Infused Hierarchical Learning: An Application in Flood Mapping on Earth Imagery"
authors:
- Zelin Xu
- Tingsong Xiao
- admin
- Yu Wang
- Zhe Jiang
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *The 31st ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems (GIS)*
publication_short: In *ACM SIGSPATIAL 2023* **[Best Paper Award]**


abstract: Deep learning for Earth imagery plays an increasingly important role in geoscience applications such as agriculture, ecology, and natural disaster management. Still, progress is often hindered by the limited training labels. Given Earth imagery with limited training labels, a base deep neural network model, and a spatial knowledge base with label constraints, our problem is to infer the full labels while training the neural network. The problem is challenging due to the sparse and noisy input labels, spatial uncertainty within the label inference process, and high computational costs associated with a large number of sample locations. Existing works on neuro-symbolic models focus on integrating symbolic logic into neural networks (e.g., loss function, model architecture, and training label augmentation), but these methods do not fully address the challenges of spatial data (e.g., spatial uncertainty, the trade-off between spatial granularity and computational costs). To bridge this gap, we propose a novel Spatial Knowledge-Infused Hierarchical Learning (SKI-HL) framework that iteratively infers sample labels within a multi-resolution hierarchy. Our framework consists of a module to selectively infer labels in different resolutions based on spatial uncertainty and a module to train neural network parameters with uncertainty-aware multi-instance learning. Extensive experiments on real-world flood mapping datasets show that the proposed model outperforms several baseline methods. The code is available at https://github.com/ZelinXu2000/SKI-HL.

# Summary. An optional shortened abstract.
summary: We propose a novel Spatial Knowledge-Infused Hierarchical Learning (SKI-HL) framework that iteratively infers sample labels within a multi-resolution hierarchy.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/ZelinXu2000/SKI-HL'
url_dataset: 'https://github.com/ZelinXu2000/SKI-HL'
url_poster: 'https://github.com/ZelinXu2000/SKI-HL'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/). -->
