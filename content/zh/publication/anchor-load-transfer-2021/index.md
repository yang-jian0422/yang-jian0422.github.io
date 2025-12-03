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
date: "2021-10-01T00:00:00Z"
doi: "https://doi.org/10.11779/CJGE202110016"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-16T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*岩土工程学报, 43*(10), 1896-1904+1959"
# publication_short: "Eng. Geol."

abstract: 基于支盘式锚杆室内模型拉拔试验，探究荷载-位移曲线的变化特征和轴力传递特性，然后在此基础上探讨支盘式锚杆的力学模型，推导出盘端阻力的理论计算公式，结合锚-土界面的双曲线非线性模型，采用分段变形协调迭代算法建立荷载传递计算模型，并与实测数据进行对比验证，最后对极限扩孔压力分布、支盘挤扩角等参数进行敏感性分析。研究结果表明，荷载-位移曲线可划分为三阶段，轴力分布沿锚固体深度呈减小趋势且在支盘处发生台阶状突变，荷载比也不断增长；计算模型所得结果与室内实测数据基本一致，验证了本模型的有效性：支盘的极限扩孔压力沿支盘径向先快速非线性增长后缓慢减小，其峰值随着位移增大而增大并以支盘中心为圆点径向外移，整体分布由“锥台状”发展为“圆柱状”；挤扩角大于50°时，对锚杆承载性状影响显著。研究结果对支盘式锚杆的受力分析和设计具有重要的理论及实际意义。

# Summary. An optional shortened abstract.
summary: 基于室内支盘式锚杆拉拔试验，分析荷载-位移特征与轴力传递规律，建立考虑界面双曲线非线性的分段迭代荷载传递模型并验证有效性。结果显示：荷载-位移曲线呈三阶段，轴力在支盘处突变；极限扩孔压力由“锥台状”向“圆柱状”演化；挤扩角>50°时对承载力影响显著。研究对支盘式锚杆设计具有重要意义。

tags:
- 支盘式锚杆
- 扩孔理论
- 非线性
- 荷载传递
- 数值计算
featured: true

links:
 - name: "Full Text (CNKI)"
   url: "https://kns.cnki.net/kcms2/article/abstract?v=dSUnQCB_TmN8B1PkpaWMsIR9NUBnt0agc_02gh9_aXcrBp43QVALmY4Wa8U55-PewKYmq03-g89zZK1Yv2MYzCioEuKGt-rNT2PsLyyVsTSpGdgnGD1I1aoXjwg2vT16dd4O4E4reMDf_FkfJGL593t_m93kU581zHKkoXeMAeBqcCkCkyaVrA&uniplatform=NZKPT&language=CHS&captchaId=0cb53655-0188-409f-879c-21b613d48263"
url_pdf: 'zh/publication/journal-article/anchor-load-transfer-2021/paper.pdf'
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
  preview_only: ture #false #控制该图片是否只用于列表页预览。false：图片会显示在列表页和正文页。true：仅在列表页显示，不会出现在正文顶部。

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
{{% callout note %}}

室内模型试验表明：相较于普通锚杆，支盘式锚杆的抗拔承载力得到了显著提高，其荷载-位移曲线可划分为3个阶段，支盘端土体塑性区随荷载增加不断向外延伸发展，当支盘达到极限强度时破裂失效，位移急剧增加，轴力分布沿锚固体深度呈减小趋势且在支盘处发生台阶状突变，荷载比也不断增长。
{{% /callout %}}

<p align="center">
  <img src="1.png" width="90%">
</p>

{{% callout note %}}
通过借鉴静力触探试验锥阻力的计算方法,引用经典的 VESIC 扩孔理论模拟支盘拉拔过程中的挤土效应,推导出盘端阻力的计算理论式。
{{% /callout %}}

<p align="center">
  <img src="2.png" width="85%">
</p>

当 $r_{0}\leq r_{x}\leq(s_{m}\tan \theta+r_{0})$ 时：

$$
P_u=Ccot\varphi(1+sin\varphi){\left[\frac{G(1+\Delta-(\frac{r_0}{r_x})^2)}{Ccos\varphi+G\Delta}\right]}^{\frac{sin\varphi}{1+sin\varphi}}-Ccot\varphi 
$$

当 $(s_m\tan \theta+r_0)\leq r_x\leq R$ 时：

$$
P_u=Ccot\varphi(1+sin\varphi)\left[\frac{G(1+\Delta-(\frac{r_x-s_m\tan(\theta)}{r_x})^2)}{Ccos\varphi+G\Delta}\right]^{\frac{sin\varphi}{1+sin\varphi}}-Ccot\varphi 
$$

{{% callout note %}}
锚-土界面选用双曲线非线性模型，采用分段变形协调迭代算法建立荷载传递计算模型。
{{% /callout %}}

<p align="center">
  <img src="featured.png" width="100%">
</p>

{{% callout note %}}
支盘的极限扩孔压力沿支盘径向先快速非线性增长后缓慢减小，其峰值随着位移增大而增大并以支盘中心为圆点径向外移，整体分布由“锥台状”发展为“圆柱状” 。支盘的挤扩角大于 50°时，对锚杆承载性状影响显著。
{{% /callout %}}

<p align="center">
  <img src="3.png" width="85%">
</p>


