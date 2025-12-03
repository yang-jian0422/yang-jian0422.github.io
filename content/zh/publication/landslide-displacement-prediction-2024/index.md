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

abstract: 为克服现有滑坡位移预测模型的局限性，本研究构建了一种融合贝叶斯优化与时间卷积网络（BO-TCN）的新型预测方法，并充分考虑研究区滑坡物理机制的动态演化特征。该模型能够自动从复杂的多变量时序数据中提取有效特征，并在训练过程中避免未来信息泄漏。同时，引入贝叶斯优化以高效搜索最优超参数，提高模型调参过程的透明度和可解释性。相比循环神经网络（RNN）类模型，BO-TCN 具有更灵活的感受野，可实现更快的训练速度和高效的并行计算。最后，利用福建省安溪县尧山滑坡的长期监测数据验证模型性能。研究结果表明，BO-TCN 均显著优于多种基准模型，预测精度更高。

# Summary. An optional shortened abstract.
summary: 为突破现有滑坡位移预测模型的局限，本研究提出一种结合贝叶斯优化与时间卷积网络（BO-TCN）的新方法，可自动提取多源时序特征并避免未来信息泄漏；贝叶斯优化用于高效寻优超参数并提升模型可解释性。与 RNN 类模型相比，BO-TCN 具有更灵活的感受野和更高的训练效率。基于尧山滑坡长期监测数据的验证结果表明，该模型显著优于多种基准算法。

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
  <img src="featured.png" width="95%">
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


