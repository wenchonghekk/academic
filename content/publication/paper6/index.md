---
title: "Weakly Supervised Spatial Deep Learning based on Imperfect Vector Labels with Registration Errors"
authors:
- Zhe Jiang
- admin
- Marcus Kirby
- Sultan Asiri
- Da Yan
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
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery and Data Mining*
publication_short: In *ACM SIGKDD 2021* 


abstract: This paper studies weakly supervised learning on spatial raster data based on imperfect vector training labels. Given raster feature imagery and imperfect (weak) vector labels with location registration errors, our goal is to learn a deep learning model for pixel classification and refine vector labels simultaneously. The problem is important in many geoscience applications such as streamline delineation and road mapping from earth imagery, where annotating imperfect coarse vector labels is far more efficient than drawing precise labels. But the problem is challenging due to the misalignment of vector labels with raster feature pixels and the need to infer true vector label location while learning neural network parameters. Existing works on weakly supervised learning often focus on noise and errors in label semantics, assuming label locations to be either correct or irrelevant (e.g., identical and independently distributed). A few works exist on label registration errors, but these methods often focus on label misalignment on object segment boundaries at the pixel level without guaranteeing vector continuity. To fill the gap, this paper proposes a spatial learning framework based on Expectation-Maximization that iteratively updates deep neural network parameters while inferring true vector label locations. Specifically, inference of true vector locations is based on both the current pixel class predictions and the geometric properties of vectors. Evaluations on real-world high-resolution remote sensing datasets in National Hydrography Dataset (NHD) refinement show that the proposed framework outperforms baseline methods in classification accuracy and refined vector quality.



# Summary. An optional shortened abstract.
summary: We proposes a spatial learning framework based on Expectation-Maximization that iteratively updates deep neural network parameters while inferring true vector label locations. 

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3447548.3467301'
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
