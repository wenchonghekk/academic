---
title: "Quantifying and Reducing Registration Uncertainty of Spatial Vector Labels on Earth Imagery"
authors:
- admin
- Zhe Jiang
- Marcus Kriby
- Yiqun Xie
- Xiaowei Jia
- Da Yan
- Yang Zhou
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2022-08-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining*
publication_short: In *KDD 2022* 


abstract: Given raster imagery features and imperfect vector training labels with registration uncertainty, this paper studies a deep learning framework that can quantify and reduce the registration uncertainty of training labels as well as train neural network parameters simultaneously. The problem is important in broad applications such as streamline classification on Earth imagery or tissue segmentation on medical imagery, whereby annotating precise vector labels is expensive and time-consuming. However, the problem is challenging due to the gap between the vector representation of class labels and the raster representation of image features and the need for training neural networks with uncertain label locations. Existing research on uncertain training labels often focuses on uncertainty in label class semantics or characterizes label registration uncertainty at the pixel level (not contiguous vectors). To fill the gap, this paper proposes a novel learning framework that explicitly quantifies vector labels' registration uncertainty. We propose a registration-uncertainty-aware loss function and design an iterative uncertainty reduction algorithm by re-estimating the posterior of true vector label locations distribution based on a Gaussian process. Evaluations on real-world datasets in National Hydrography Dataset refinement show that the proposed approach significantly outperforms several baselines in the registration uncertainty estimations performance and classification performance.


# Summary. An optional shortened abstract.
summary: We propose uncertainty aware weakly supervised learning framework with registration error on Earth Imagery .

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3534678.3539410'
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
