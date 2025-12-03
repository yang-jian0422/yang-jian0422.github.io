---
title: "注浆支盘式锚杆拉拔试验及极限承载力计算"
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
date: "2021-05-01T00:00:00Z"
doi: "https://10.16285/j.rsm.2020.1362"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-04-22T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*岩土力学, 42*(04), 1126-1132"
# publication_short: "Eng. Geol."

abstract: 注浆支盘式锚杆是自主研发的一种新型锚杆,具有广阔的应用前景。为了探究支盘式锚杆的承载特性,构建室内试验模型,针对不同的埋置深度、支盘直径和双支盘间距等条件进行拉拔试验,获取相应的荷载-位移曲线,并对部分数据采取无量纲化处理得到埋深比与荷载系数关系曲线,最后通过简化力学模型推导出支盘式锚杆的端阻力与拉拔极限承载力的计算公式。研究结果表明,埋置深度与极限承载力呈非线性关系且存在临界埋深;盘径对抗拔承载力的影响最为显著,与极限承载力呈线性增长关系,极限承载力较普通锚杆提高了2～5倍多;双支盘的分界间距为4倍支盘直径时可充分调用双支盘的承载力,由于双支盘锚杆在加载初期时土体主要为剪切变形,故其荷载-位移曲线开始阶段斜率较单支盘锚杆要大得多;埋深比与荷载系数关系曲线的斜率突变点为临界埋深比,其值为3.02;该计算公式所得结果与4组试验结果基本一致,验证了计算公式的有效性。研究结果对支盘式锚杆的设计和工程应用具有重要的理论及实际意义。

# Summary. An optional shortened abstract.
summary: 基于自主研发的注浆支盘式锚杆，开展不同埋置深度、盘径和双盘间距条件下的室内拉拔试验，获取荷载–位移曲线并进行无量纲化分析，推导端阻力及极限承载力公式。结果表明：埋深与承载力呈非线性关系并存在临界埋深；盘径对承载力影响最显著，使承载力提高2–5倍；双支盘最佳间距为4D；埋深比临界值为3.02。

tags:
- 支盘式锚杆
- 极限承载力
- 拉拔试验
- 端阻力

featured: true

links:
 - name: "Full Text (CNKI)"
   url: "https://kns.cnki.net/kcms2/article/abstract?v=UsPV4INcYzhMZpB0zQGCFyPARWC465i4EW7mGheWyJx2puDR1LhUHu8TrYQLVb-2tCdkLDz_nPV7g_LqLVpMNJZu5qGK5ql1skGmuY-w2KQfsEozD_GPE6KHYuBVxwAV5G-TdevBibFCwBfxKMUACQm2dMbg1klUA9K_9R4gc7Tju6z0wAz0_VAlj0P0HqNs_qL-gbl0Fc0&uniplatform=NZKPT&captchaId=494dfc1b-c395-4810-94bc-fb44775ab332"
url_pdf: 'zh/publication/journal-article/Pull-out-test-2021/paper.pdf'
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

支盘式锚杆是通过自主研发的扩孔设备在指定土层形成支盘状空腔，然后注浆形成多支盘锚固体结构。相较于传统锚索、扩大头锚杆具有以下优点：

- 抗拔承载力高——有限锚杆长度
- 鲁棒性强——多个支盘
- 灵活性强——可选择工程性能良好的土层形成支盘

<p align="center">
  <img src="3.png" width="75%">
</p>

---
{{% callout note %}}

盘径与极限承载力呈线性增长关系， 不同支盘直径 $D$ 的锚杆较直锚杆的极限承载力提高了 2～5 倍，说明盘径对抗拔承载力的影响最为显著。随着双支盘间距的增大，极限抗拔承载力也逐步加大，当分界间距为 4 倍支盘直径时，可充分调用双支盘的承载力。
{{% /callout %}}

<p align="center">
  <img src="2.png" width="75%">
</p>

{{% callout note %}}
支盘式锚杆的埋置深度与极限承载力呈非线性增加，当埋深达到 500 mm 后极限承载力变化幅度逐步降低（存在临界埋深）；埋深比与荷载系数关系曲线的斜率突变点为临界埋深比，$(H/D)_{\mathrm{CR}}$ =3.02。
{{% /callout %}}

描述锚杆的支盘埋置深度对极限抗拔力的影响，无量纲荷载系数 $N_{\mathrm{pf}}$ 定义为:

$$
N_{\mathrm{pf}}=P_\mathrm{f}/AK_0\gamma H
$$
式中：$P_\mathrm{f}$ 为锚杆的极限拉拔力； $A$ 为支盘面积（ $A=\pi R^2$ ）； $K_0$ 为支盘前土体的静止土压力系数；$H$ 为支盘埋置的深度；$\gamma$ 为上覆土的重度。

<p align="center">
  <img src="1.png" width="75%">
</p>

{{% callout note %}}
随着拉拔力的增加，盘端土体产生压缩挤密作用，锚杆轴向土体应力转化为第一主应力并达到极限压力，盘端阻力显著增加，推导得出的支盘式锚杆极限承载力计算公式与试验结果基本一致，验证了计算公式的有效性。
{{% /callout %}}

支盘锚杆的承载力主要有两部分组成：支盘端阻力与锚固段的侧阻力。极限承载力可表示为

$$
P_\mathrm{f}=P_\mathrm{s}+Q
$$

$$
P_\mathrm{s}=\pi d(L-L_\mathrm{p})q_\mathrm{s}
$$

盘端阻力 $Q$ 可表示为
$$
Q=\frac{\pi(R^2-r^2)\left[(1-\xi)K_0K_\mathrm{P}\sum\gamma H+2c\sqrt{K_\mathrm{P}}\right]}{(1-\xi K_\mathrm{P})\tan\theta}
$$

<p align="center">
  <img src="4.png" width="80%">
</p>


