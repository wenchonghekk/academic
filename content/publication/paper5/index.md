---
title: "Earth Imagery Segmentation on Terrain Surface with Limited Training Labels: A Semi-supervised Approach based on Physics-Guided Graph Co-Training"
authors:
- admin
- Zhe Jiang
- Arpan Man Sainju
- Da Yan
- Yang Zhou
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2022-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: In *ACM Transactions on Intelligent Systems and Technology*
publication_short: In *ACM TIST 2022* 


abstract: Given earth imagery with spectral features on a terrain surface, this paper studies surface segmentation based on both explanatory features and surface topology. The problem is important in many spatial and spatiotemporal applications such as flood extent mapping in hydrology. The problem is uniquely challenging for several reasons:first, the size of earth imagery on a terrain surface is often much larger than the input of popular deep convolutional neural networks; second, there exists topological structure dependency between pixel classes on the surface, and such dependency can follow an unknown and non-linear distribution; third, there are often limited training labels. Existing methods for earth imagery segmentation often divide the imagery into patches and consider the elevation as an additional feature channel. These methods do not fully incorporate the spatial topological structural constraint within and across surface patches and thus often show poor results, especially when training labels are limited. Existing methods on semi-supervised and unsupervised learning for earth imagery often focus on learning representation without explicitly incorporating surface topology. In contrast, we propose a novel framework that explicitly models the topological skeleton of a terrain surface with a contour tree from computational topology, which is guided by the physical constraint (e.g., water flow direction on terrains). Our framework consists of two neural networks:a convolutional neural network (CNN) to learn spatial contextual features on a 2D image grid, and a graph neural network (GNN) to learn the statistical distribution of physics-guided spatial topological dependency on the contour tree. The two models are co-trained via variational EM. Evaluations on the real-world flood mapping datasets show that the proposed models outperform baseline methods in classification accuracy, especially when training labels are limited.



# Summary. An optional shortened abstract.
summary: We propose a novel framework that explicitly models the topological skeleton of a terrain surface with a contour tree from computational topology, which is guided by the physical constraint (e.g., water flow direction on terrains). 

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://dl.acm.org/doi/full/10.1145/3481043'
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
