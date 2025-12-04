---
title: 支盘式锚杆拉拔荷载传递非线性分析软件

event: Hugo Blox Builder Conference
event_url: https://example.org

location: Hugo Blox Builder HQ
address:
  street: 450 Serra Mall
  city: Stanford
  region: CA
  postcode: '94305'
  country: United States

summary: An example talk using Hugo Blox Builder's Markdown slides feature.
abstract: 支盘式锚杆拉拔荷载传递非线性分析软件根据工程实际情况，对边坡土的物理（粘聚力、摩擦角以及泊松比等）、支盘式锚杆（挤扩角、支盘半径以及弹性模量等）和网格划分等参数赋值，通过灵活调用不同的荷载传递模型，对支盘式锚杆拉拔荷载传递的非线性受力性状进行全历程分析，绘制出荷载—位移曲线和沿轴向深度的轴力分布图。该软件主要有如下特点：（1）荷载传递模型的可选择性。基于不同的工程实际情况，可灵活调用不同的荷载传递模型（如双曲线模型、硬化模型和软化模型等）分别进行计算，从而对实际工程进行有效预测；（2）计算参数赋值智能化。软件与Excel文件格式耦合性好，支持Excel数据的提取和保存；（3）考虑边坡土的成层性。支持将支盘式锚杆划分为不同锚杆段数进行计算；（4）软件的可扩充性。该软件为开放式软件，在实际应用过程中随着对支盘式锚杆研究的不断加深，可不断地扩充更好反映支盘式锚杆工作性状的荷载传递模型及支盘端阻力计算模型；（5）软件采用MATLAB GUI编写，具有良好的可移植性。

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2030-06-01T13:00:00Z'
date_end: '2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: 'https://github.com'
url_pdf: ''
url_slides: 'https://slideshare.net'
url_video: 'https://youtube.com'

image:
 focal_point: "Center"

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - example
---

{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page.
