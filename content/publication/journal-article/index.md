---
title: "SketchRefiner: Text-Guided Sketch Refinement through Latent Diffusion Models"
authors:
- admin
- Yingjie Tian
- etc.
author_notes:
# - "Equal contribution"
# - "Equal contribution"
# date: "2015-09-01T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# # Publication type.
# # Accepts a single type but formatted as a YAML list (for Hugo requirements).
# # Enter a publication type from the CSL standard.
# publication_types: ["article-journal"]

# # Publication name and optional abbreviated publication name.
# publication: "*Journal of Source Themes, 1*(1)"
# publication_short: ""

abstract: Free-hand sketches serve as efficient tools for creativity and communication, yet expressing ideas clearly through sketches remains challenging for untrained individuals. Optimizing sketches through text guidance can enhance individuals' ability to effectively convey their ideas and improve overall communication efficiency. While recent advancements in Artificial Intelligence Generated Content (AIGC) have been notable, research on optimizing free-hand sketches remains relatively unexplored. In this paper, we introduce SketchRefiner, an innovative method designed to refine rough sketches from various categories into polished versions guided by text prompts. SketchRefiner utilizes a latent diffusion model with ControlNet to guide a differentiable rasterizer in optimizing a set of Bézier curves. We extend the score distillation sampling (SDS) loss and introduce a joint semantic loss to encourage sketches aligned with given text prompts and free-hand sketches. Additionally, we propose a fusion attention-map stroke initialization strategy to improve the quality of refined sketches. Furthermore, SketchRefiner provides users with fine-grained control over text guidance. Through extensive experiments, we demonstrate that our method can generate accurate and aesthetically pleasing refined sketches that closely align with input text prompts and sketches.

# Summary. An optional shortened abstract.
summary: Our paper introduces SketchRefiner, a method that uses text guidance and a latent diffusion model to transform rough free-hand sketches into refined versions, improving communication efficiency and creativity.

tags:
- Sketch Refinement
- Diffusion Model
featured: ture

# links:
# - name: ""
#   url: ""
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

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
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
