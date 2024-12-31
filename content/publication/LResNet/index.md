---
title: 'Lorentzian Residual Neural Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Menglin Yang
  - Rex Ying

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-12-17'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2025 ACM SIGKDD*
publication_short: In *SIGKDD'25*

abstract: Hyperbolic neural networks have emerged as a powerful tool for modeling hierarchical data structures prevalent in real-world datasets. Notably, residual connections, which facilitate the direct flow of information across layers, have been instrumental in the success of deep neural networks. However, current methods for constructing hyperbolic residual networks suffer from limitations such as increased model complexity, numerical instability, and errors due to multiple mappings to and from the tangent space. To address these limitations, we introduce LResNet, a novel Lorentzian residual neural network based on the weighted Lorentzian centroid in the Lorentz model of hyperbolic space. Our method enables the efficient integration of residual connections in Lorentz hyperbolic neural networks while preserving their hierarchical representation capabilities. We demonstrate that our method can theoretically derive previous methods while offering improved stability, efficiency, and effectiveness. Extensive experiments on both graph and vision tasks showcase the superior performance and robustness of our method compared to state-of-the-art Euclidean and hyperbolic alternatives. Our findings highlight the potential of LResNet for building more expressive neural networks in hyperbolic embedding space as a generally applicable method to multiple architectures, including CNNs, GNNs, and graph Transformers.

# Summary. An optional shortened abstract.
# summary: LResNet

tags:
  - Hyperbolic Representation Learning

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2412.14695'
url_code: 'https://github.com/Graph-and-Geometric-Learning/LResNet'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: ''
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
