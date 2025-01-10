---
title: 'RecMoDiffuse: Recurrent Flow Diffusion for Human Motion Generation'
authors:
- admin
- Harry Jake Cunningham
- Marc P Deisenroth
- Lourdes Agapito
date: '2024-01-01'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-10-31T19:15:09.992572Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ['paper-conference']
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: '*arXiv preprint arXiv:2406.07169*'
publication_short: In *ICW*

abstract: 'Human motion generation has paramount importance in computer animation. It is a challenging generative temporal modelling task due to the vast possibilities of human motion, high human sensitivity to motion coherence and the difficulty of accurately generating fine-grained motions. Recently, diffusion methods have been proposed for human motion generation due to their high sample quality and expressiveness. However, generated sequences still suffer from motion incoherence, and are limited to short duration, and simpler motion and take considerable time during inference. To address these limitations, we propose RecMoDiffuse: Recurrent Flow Diffusion, a new recurrent diffusion formulation for temporal modelling. Unlike previous work, which applies diffusion to the whole sequence without any temporal dependency, an approach that inherently makes temporal consistency hard to achieve. Our method explicitly enforces temporal constraints with the means of normalizing flow models in the diffusion process and thereby extends diffusion to the temporal dimension. We demonstrate the effectiveness of RecMoDiffuse in the temporal modelling of human motion. Our experiments show that RecMoDiffuse achieves comparable results with state-of-the-art methods while generating coherent motion sequences and reducing the computational overhead in the inference stage.'

# Summary. An optional shortened abstract.
summary: 'We develop a novel architecture RecMoDiffuse: Recurrent Flow Diffusion, a new recurrent diffusion formulation for temporal modelling. Our method explicitly enforces temporal constraints with the means of normalizing flow models in the diffusion process and thereby extends diffusion to the temporal dimension.'

tags:
  - Diffusion Models
  - Human Motion Generation
  - Recurrent

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2406.07169'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://mirgahney.github.io/rfdm.io/'
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

# {{% callout note %}}
# Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}
# 
# {{% callout note %}}
# Create your slides in Markdown - click the _Slides_ button to check out the example.
# {{% /callout %}}
# 
# Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
---
