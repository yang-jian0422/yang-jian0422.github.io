---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  spacing: '5rem'

sections:
  # 第一部分：研究兴趣介绍（文字块）
  - block: hero
    content:
      title: Selected Projects
      text: >
        I have a wide interest in all phenomena relating to the initiation and movement of landslides.
        My current research mainly focuses on:
        
        1. Initiation and movement mechanisms of rapid long-travel landslides  
        2. Prediction of landsliding via geotechnical experiments  
        3. Generation and maintenance of excess pore-water pressure and landsliding  
        4. Formation of fluidized soil layer structures and landslide movement  
        5. Risk assessment of large-scale reactivated landslides  
        6. Instability of landslide dams and hazard mitigation  
        7. Landslides occurring under extreme weather  
        8. Shear behavior of landslide clay and fault gouge  
        
        The research approaches include:  
        - Laboratory tests (ring shear tests and flume tests)  
        - Field investigations (landslide monitoring, Surface-Wave surveys, tremor and seismic monitoring)  
        - Theoretical analysis (continuum mechanics, granular material mechanics)
    design:
      align: wide  # 让文字横向铺展，提升可读性
      #justify: left
      #background:
      #  color: light


  # 第二部分：项目卡片展示
  - block: collection
    content:
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: false
      columns: 3
---
