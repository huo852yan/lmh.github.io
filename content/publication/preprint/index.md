---
title: "CLIPRefiner: Enhancing Realism and Detail in Free-Hand Sketches through Semantically-Aware Optimization"
authors:
- admin
- Yingjie Tian
# date: "2019-04-07T00:00:00Z"
# doi: ""

# # Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# # Publication type.
# # Accepts a single type but formatted as a YAML list (for Hugo requirements).
# # Enter a publication type from the CSL standard.
# publication_types: ["article"]

# # Publication name and optional abbreviated publication name.
# publication: ""
# publication_short: ""

abstract: Free-hand sketches are a fundamental tool for individuals to translate their internal perceptions of the world, bridging the gap between the abstract and the concrete. However, not everyone possesses the innate ability to convey their ideas through sketches, often resulting in sketches with certain limitations. Consequently, refining rough sketches into polished representations presents an intriguing challenge for both humans and machines. This study introduces CLIPRefiner, an innovative method that harnesses a pre-trained CLIP model to transform rough sketches from various categories into polished renditions. CLIPRefiner smoothens and optimizes two sets of Bézier curves, combining global and local optimization processes to enhance image semantics and enrich sketch details, all without the need for a dedicated sketch dataset for training. Notably, CLIPRefiner's local strokes initialization resampling significantly expedites the convergence process. Qualitative and quantitative experiments compellingly demonstrate CLIPRefiner's ability to transform rough sketches into high-quality, refined versions. The user study underscores the enhanced semantic perception of sketches refined by CLIPRefiner, while the ablation study provides valuable insights into the effectiveness of each module within CLIPRefiner. Additionally, CLIPRefiner has the potential to contribute a valuable rough-fine paired sketch dataset to the broader sketching community. 

# Summary. An optional shortened abstract.
summary: Our study presents CLIPRefiner, a method leveraging a pre-trained CLIP model to transform rough sketches into polished versions by optimizing Bézier curves for enhanced semantics and detail, all without requiring a dedicated training dataset.

tags:
- CLIPRefiner
- Bézier Curves 

featured: false

# links:
# - name: Custom Link
#   url: http://example.org
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# # Featured image
# # To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# # Associated Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.
# projects:
# - internal-project

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example
# ---

# This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

# {{% callout note %}}
# Create your slides in Markdown - click the *Slides* button to check out the example.
# {{% /callout %}}

# Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
