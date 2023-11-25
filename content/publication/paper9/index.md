---
title: "CurvaNet: Geometric Deep Learning based on Directional Curvature for 3D Shape Analysis"
authors:
- admin
- Zhe Jiang
- Chengming Zhang
- Arpan Man Sainju
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2021-08-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 26th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining*
publication_short: In *ACM SIGKDD 2020* 


abstract: Over the last decade, deep learning research has achieved tremendous success in computer vision and natural language processing. The current widely successful deep learning models are largely based on convolution and pooling operations on a Euclidean plane with a regular grid (e.g., image and video data) and thus cannot be directly applied to the non-Euclidean surface. Geometric deep learning aims to fill the gap by generalizing deep learning models from a 2D Euclidean plane to a 3D geometric surface. The problem has important applications in human-computer interaction, biochemistry, and mechanical engineering, but is uniquely challenging due to the lack of a regular grid framework and the difficulties in learning geometric features on a non-Euclidean manifold. Existing works focus on generalizing deep learning models from 2D image to graphs (e.g., graph neural networks) or 3D mesh surfaces but without fully learning geometric features from a differential geometry perspective. In contrast, this paper proposes a novel geometric deep learning model called CurvaNet that integrates differential geometry with graph neural networks. The key idea is to learn direction sensitive 3D shape features through directional curvature filters. We design a U-Net like architecture with downsampling and upsampling paths based on mesh pooling and unpooling operations. Evaluation on real-world datasets shows that the proposed model outperforms several baseline methods in classification accuracy.






# Summary. An optional shortened abstract.
summary: We proposes a novel geometric deep learning model called CurvaNet that integrates differential geometry with graph neural networks. 

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3394486.3403272'
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
