---
title: "注浆支盘式锚杆拉拔荷载传递非线性分析"
authors:
- admin
- 简文彬
- 黄炜
- 黄聪惠
- 罗金妹
- 李先忠
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2025-09-01T00:00:00Z"
doi: "https://doi.org/10.11779/CJGE202110016"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-16T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "*岩土工程学报, 43*(10)"
# publication_short: "Eng. Geol."

abstract: 基于支盘式锚杆室内模型拉拔试验，探究荷载-位移曲线的变化特征和轴力传递特性，然后在此基础上探讨支盘式锚杆的力学模型，推导出盘端阻力的理论计算公式，结合锚-土界面的双曲线非线性模型，采用分段变形协调迭代算法建立荷载传递计算模型，并与实测数据进行对比验证，最后对极限扩孔压力分布、支盘挤扩角等参数进行敏感性分析。研究结果表明，荷载-位移曲线可划分为三阶段，轴力分布沿锚固体深度呈减小趋势且在支盘处发生台阶状突变，荷载比也不断增长；计算模型所得结果与室内实测数据基本一致，验证了本模型的有效性：支盘的极限扩孔压力沿支盘径向先快速非线性增长后缓慢减小，其峰值随着位移增大而增大并以支盘中心为圆点径向外移，整体分布由“锥台状”发展为“圆柱状”；挤扩角大于50°时，对锚杆承载性状影响显著。研究结果对支盘式锚杆的受力分析和设计具有重要的理论及实际意义。

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- 支盘式锚杆
- 扩孔理论
- 非线性
- 荷载传递
- 数值计算
featured: true

links:
 - name: "Full Text (Elsevier)"
   url: "https://www.sciencedirect.com/science/article/abs/pii/S0013795225002133?via%3Dihub"
url_pdf: 'zh/publication/journal-article1/paper.pdf'
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: "Top" # 指定图片的焦点区域，用于自动裁剪时对齐。可选值包括 "Center", "TopLeft", "BottomRight" 等。这里为空 ""，表示默认居中。
  preview_only: false #控制该图片是否只用于列表页预览。false：图片会显示在列表页和正文页。true：仅在列表页显示，不会出现在正文顶部。

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

## 插图示例

<p align="center">
  <img src="featured.png" width="75%">
</p>

**图 1** 支盘式锚杆拉拔荷载传递机制示意图。

$$
p_\mathrm{u}=c\cot\varphi(1+\sin\varphi){\left(\frac{R_\mathrm{p}}{R_\mathrm{u}}\right)^{\frac{2\sin\varphi}{1+\sin\varphi}}-c\cot\varphi}
$$

---
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
