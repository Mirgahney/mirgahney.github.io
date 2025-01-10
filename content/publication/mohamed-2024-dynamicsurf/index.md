---
title: 'Dynamicsurf: Dynamic neural rgb-d surface reconstruction with an optimizable
  feature grid'
authors:
- admin
- Lourdes Agapito
date: '2024-01-01'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-10-31T19:15:09.978668Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: '*2024 International Conference on 3D Vision (3DV)*'
publication_short: In *ICW*

abstract: We propose DynamicSurf, a model-free neural implicit surface reconstruction method for high-fidelity 3D modelling of non-rigid surfaces from monocular RGB-D video. To cope with the lack of multi-view cues in monocular sequences of deforming surfaces, one of the most challenging settings for 3D reconstruction, DynamicSurf exploits depth, surface normals, and RGB losses to improve reconstruction fidelity and optimisation time. DynamicSurf learns a neural deformation field that maps a canonical representation of the surface geometry to the current frame. We depart from current neural non-rigid surface reconstruction models by designing the canonical representation as a learned feature grid which leads to faster and more accurate surface reconstruction than competing approaches that use a single MLP. We demonstrate DynamicSurf on public datasets and show that it can optimize sequences of varying frames with 6× speedup over pure MLP-based approaches while achieving comparable results to the state-of-the-art methods. 

# Summary. An optional shortened abstract.
summary: We propose a model-free neural implicit surface reconstruction method for high-fidelity 3D modelling of non-rigid surfaces from monocular RGB-D video. 

tags:
  - Dynamic Surface Reconstruction
  - Optimizable Feature Grid
  - RGB-D Reconstruction

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2311.08159'
url_code: 'https://github.com/Mirgahney/dynsurf'
url_dataset: ''
url_poster: ''
url_project: 'https://mirgahney.github.io//DynamicSurf.io/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example

#{{% callout note %}}
#Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
#{{% /callout %}}
#
#{{% callout note %}}
#Create your slides in Markdown - click the _Slides_ button to check out the example.
#{{% /callout %}}
#
#Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
---
