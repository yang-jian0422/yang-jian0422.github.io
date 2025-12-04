---
title: 支盘式锚杆拉拔荷载传递非线性分析软件

# event: Hugo Blox Builder Conference
# event_url: https://example.org

# location: Hugo Blox Builder HQ
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: 支盘式锚杆拉拔荷载传递非线性分析软件可根据工程条件输入土体参数（黏聚力、内摩擦角、泊松比等）、锚杆参数（挤扩角、盘径、弹性模量等）及网格信息，利用不同荷载传递模型对锚杆全历程受力进行分析，并输出荷载—位移曲线与轴力分布。其主要特点包括：① 可灵活选择双曲线、硬化、软化等模型以适应不同工程需求；② 参数读取与保存均可与 Excel 互通，实现智能化赋值；③ 可考虑边坡土层分段，支持多锚段计算；④ 具备开放性，可随研究进展扩展模型库；⑤ 基于 MATLAB GUI 开发，移植性良好。
abstract: 支盘式锚杆拉拔荷载传递非线性分析软件根据工程实际情况，对边坡土的物理（粘聚力、摩擦角以及泊松比等）、支盘式锚杆（挤扩角、支盘半径以及弹性模量等）和网格划分等参数赋值，通过灵活调用不同的荷载传递模型，对支盘式锚杆拉拔荷载传递的非线性受力性状进行全历程分析，绘制出荷载—位移曲线和沿轴向深度的轴力分布图。该软件主要有如下特点：（1）荷载传递模型的可选择性。基于不同的工程实际情况，可灵活调用不同的荷载传递模型（如双曲线模型、硬化模型和软化模型等）分别进行计算，从而对实际工程进行有效预测；（2）计算参数赋值智能化。软件与Excel文件格式耦合性好，支持Excel数据的提取和保存；（3）考虑边坡土的成层性。支持将支盘式锚杆划分为不同锚杆段数进行计算；（4）软件的可扩充性。该软件为开放式软件，在实际应用过程中随着对支盘式锚杆研究的不断加深，可不断地扩充更好反映支盘式锚杆工作性状的荷载传递模型及支盘端阻力计算模型；（5）软件采用MATLAB GUI编写，具有良好的可移植性。

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2020-10-10T13:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: 
- 软件著作权

# Is this a featured talk? (true/false)
featured: false

image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Center"

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
# url_code: 'https://github.com'
# url_pdf: ''
# url_slides: 'https://slideshare.net'
# url_video: 'https://youtube.com'

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
# projects:
#   - example
---
支盘式锚杆拉拔荷载传递非线性分析软件主要由控制层、输入层、逻辑层和输出层4部分组成。

<p align="center">
  <img src="1.png" width="90%">
</p>

{{% callout note %}}
控制层实现用户对软件主界面进行操作的功能，通过主界面菜单栏支持对荷载模型选择界面、输入参数界面、软件使用帮助界面以及数值计算和绘制曲线图的运算界面的调用。
{{% /callout %}}

{{% callout note %}}
输入层是实现用户与软件进行信息交互的途径。该软件的输入层将土的物理参数（粘聚力、摩擦角、弹性模量以及泊松比等）、支盘式锚杆参数（挤扩角、支盘半径以及锚杆弹性模量等）和网格划分参数三方面进行赋值。对用户未经实测而无法确定的参数，用户可对照本区域类似工程的地质和设计参数进行比较后确定。
{{% /callout %}}

{{% callout note %}}
逻辑层是支盘式锚杆拉拔荷载传递非线性分析软件的重要部分，其核心内容是荷载传递模型（双曲线模型、硬化模型以及软化模型等）的选择。在实际工程中可根据具体情况灵活选择不同的荷载传递模型。
{{% /callout %}}

{{% callout note %}}
输出层包含模型计算、数值结果的输出和绘图（荷载-位移曲线、沿轴向深度的轴力分布图）的输出三部分，其中模型计算采用分段变形协调迭代算法。
{{% /callout %}}


