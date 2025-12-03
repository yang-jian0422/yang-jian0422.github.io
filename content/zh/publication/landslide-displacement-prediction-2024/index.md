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
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Acta Geotechnica, 19*(7), 4947-4965"
publication_short: ""

abstract: To address the limitations of existing landslide displacement prediction models, this study developed a novel approach that integrates Bayesian optimization with temporal convolutional networks (BO-TCN), considering the dynamic evolutionary characteristics of landslide physical mechanisms in the study area. The proposed model automatically extracts informative features from complex multivariate time-series datasets while preventing data leakage from future observations during training. Moreover, Bayesian optimization is employed to efficiently identify the optimal hyperparameters of the model, thereby providing deeper insight into the tuning process and model interpretability. Compared with recurrent neural network (RNN)-based models, the proposed BO-TCN framework features flexible receptive fields, enabling faster training and efficient parallel computation. Finally, the predictive performance of the proposed model was evaluated using long-term monitoring data from the Yaoshan landslide in Anxi County, Fujian Province, China. The experimental results demonstrate that the proposed model achieves superior prediction accuracy across different forecast horizons compared with several benchmark algorithms.

# Summary. An optional shortened abstract.
summary: A Bayesian optimization–temporal convolutional network (BO-TCN) model is developed for landslide displacement prediction. It autonomously extracts key features from multivariate time-series data and uses Bayesian optimization to determine optimal hyperparameters. Compared with recurrent neural networks, the BO-TCN offers faster training, flexible receptive fields, and superior parallelization.

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
  preview_only: true

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

<p align="center">
  <img src="featured.png" width="75%">
</p>

TCN 是基于传统一维 CNN 的一个简单但强大的扩展，具有以下三个特性：
- 输出序列与输入序列具有相同的长度；
- 当前时间 $t$ 的预测结果只与历史信息相关，从未来到过去不可能有信息泄漏；
- 通过使用扩张卷积，感受野以及有效记忆随着网络深度的增加呈指数增长。可以抓取滑坡演化过程中更长的历史时间序列依赖信息，提高滑坡位移预测精度。

<p align="center">
  <img src="tcn.png" width="75%">
</p>

{{% callout note %}}
针对滑坡的复杂动力学机制与非线性演化特征，所提出的 BO-TCN 模型在训练过程中有效避免了基于位移分解方法所固有的“未来数据泄露”风险。预测结果显示，该模型在多项评价指标（MAE、MSE、RMSE 与 R2）上均取得最优表现，显著优于现有的滑坡位移预测模型，具有较高的实用性与推广价值。
{{% /callout %}}

{{% callout note %}}
与静态机器学习模型（BO-RF、BO-SVM）相比，BO-TCN 能够更好地刻画滑坡位移的时变非线性规律，在动态预测任务中表现出明显优势。同时，与传统的深度学习模型（1D-CNN、LSTM、GRU）相比，BO-TCN 在捕捉尧山滑坡阶梯状变形阶段的响应特征方面具有更强的泛化能力和预测稳定性。研究结果表明，通过对降雨与孔隙水压力的实时监测并结合该模型，可实现滑坡再激活阶段的提前识别与预警。
{{% /callout %}}


