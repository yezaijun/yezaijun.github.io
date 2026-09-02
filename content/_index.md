---
title: ''
summary: '叶再俊——计算数学与科学机器学习'
date: 2026-08-08
type: landing

sections:
  - block: resume-biography
    content:
      username: me
      text: ''
    design:
      css_class: zh-home-profile-section
      name:
        size: md
      avatar:
        size: medium
        shape: square

  - block: markdown
    id: about
    content:
      title: About
      subtitle: ''
      text: |-
        我是上海师范大学计算数学专业研究生，师从王晚生教授。我的研究兴趣是 AI for CAE（人工智能驱动的计算机辅助工程），目标是开发可靠的学习型方法，在利用人工智能加速和增强工程仿真的同时，保留传统数值方法在物理精度、数值稳定性和可解释性方面的优势。
    design:
      columns: '1'
      css_class: zh-home-simple-section

  - block: collection
    id: publications
    content:
      title: Publications
      subtitle: ''
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
      css_class: zh-home-simple-section

  - block: simple-education
    id: experience
    content:
      title: Education
      username: me
    design:
      date_format: '2006年1月'
      css_class: zh-home-simple-section

  - block: markdown
    id: awards
    content:
      title: Awards
      subtitle: ''
      text: |
        - **2025年12月**　“华为杯”第二十二届中国研究生数学建模竞赛一等奖（通用神经网络处理器下的核内调度问题，负责人）
        - **2025年11月**　2025年度中国青年科技创新“揭榜挂帅”擂台赛新材料领域一等奖（先进封装结构的多尺度多物理耦合建模与仿真降阶研究，负责人）
    design:
      columns: '1'
      css_class: zh-home-simple-section

  - block: markdown
    id: projects
    content:
      title: Blogs
      subtitle: ''
      text: |
        - [面向大规模芯片热仿真的完整界面 DD-POD 快速算法](/projects/ddpod-chip-thermal-rom/)
        - [MaxV：面向 STL 几何的最大体积可行实体搜索](/projects/maxv/)
        - [从流场预测到可信优化：一次神经算子翼型设计实验](/projects/trustworthy-neural-operator-airfoil-design/)
        - [管材绕弯成形工艺仿真的神经算子方法](/projects/tube-bending-neural-operator/)
        - [NPU 核内调度的缓存分配优化模型与高效启发式算法](/projects/npu-in-core-scheduling/)
        - [先进封装结构的多尺度多物理耦合建模与智能仿真降阶](/projects/hybrid-ai-3d-packaging-rom/)
        - [AutoBrep 条件几何生成：从论文复现到 AI for CAE 工具原型](/projects/autobrep-conditional-geometry-generation/)
    design:
      columns: '1'
      css_class: zh-home-simple-section
---
