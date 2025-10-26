---
title: "Landslide displacement prediction by using Bayesian optimization–temporal convolutional networks"
authors:
- admin
- Huang Zhijie 
- Jian Wenbin 
- Luis F. Robledo 
date: "2024-07-01T00:00:00Z"
doi: "https://doi.org/10.1007/s11440-023-02205-8"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-02-06T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "*Acta Geotechnica, 19*(7), 4947-4965"
publication_short: ""

abstract: To address the limitations of existing landslide displacement prediction models, this study developed a novel approach that integrates Bayesian optimization with temporal convolutional networks (BO-TCN), considering the dynamic evolutionary characteristics of landslide physical mechanisms in the study area. The proposed model automatically extracts informative features from complex multivariate time-series datasets while preventing data leakage from future observations during training. Moreover, Bayesian optimization is employed to efficiently identify the optimal hyperparameters of the model, thereby providing deeper insight into the tuning process and model interpretability. Compared with recurrent neural network (RNN)-based models, the proposed BO-TCN framework features flexible receptive fields, enabling faster training and efficient parallel computation. Finally, the predictive performance of the proposed model was evaluated using long-term monitoring data from the Yaoshan landslide in Anxi County, Fujian Province, China. The experimental results demonstrate that the proposed model achieves superior prediction accuracy across different forecast horizons compared with several benchmark algorithms.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Landslide displacement prediction
- Temporal convolutional networks
- Bayesian optimization
- Deep learning
- Engineering geology

featured: true

links:
- name: Full Text (Springer)
  url: https://doi.org/10.1007/s11440-023-02205-8
url_pdf: https://link.springer.com/content/pdf/10.1007/s11440-023-02205-8.pdf
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: "TOP"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{< pdf src="tcn.pdf" width="100%" height="800px" >}}

{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
