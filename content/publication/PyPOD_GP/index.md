---
title: "PyPOD-GP: Using PyTorch for Accelerated Chip-Level Thermal Simulation of the GPU"
authors:
- admin
- Yu Liu
- Ming-Cheng Cheng
date: "2024-11-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: "preprint"

abstract: The rising demand for high-performance computing (HPC) has made full-chip dynamic thermal simulation in many-core GPUs critical for optimizing performance and extending device lifespans. Proper orthogonal decomposition (POD) with Galerkin projection (GP) has shown to offer high accuracy and massive runtime improvements over direct numerical simulation (DNS). However, previous implementations of POD-GP use MPI-based libraries like PETSc and FEniCS and face significant runtime bottlenecks. We propose a PyTorch-based POD-GP library (PyPOD-GP), a GPU-optimized library for chip-level thermal simulation. PyPOD-GP achieves over 23.4X speedup in training and over 10X speedup in inference on a GPU with over 13,000 cores, with just 1.2% error over the device layer.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Thermal Simulation

featured: true

links:
# - name: Custom Link
#   url: ''
url_pdf: 'https://arxiv.org/abs/2412.06041#'
url_code: 'https://github.com/784956494/PyPOD-GP'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  # focal_point: ""
  # preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- PyPOD_GP

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs. -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
