---
layout: single
title: GeoSceneGraph Annotator
permalink: /research/gsga/
author_profile: true
toc: true
toc_sticky: true
classes: project-page
header:
  overlay_image: /assets/images/projects/gsga/hero.jpg   # 替换为你的封面图
  overlay_filter: 0.35
  caption: "对象-关系三元组标注工具（GSGA）"
gallery:
  - url: /assets/images/projects/gsga/shot1.jpg
    image_path: /assets/images/projects/gsga/shot1.jpg
    alt: 标注主界面
  - url: /assets/images/projects/gsga/shot2.jpg
    image_path: /assets/images/projects/gsga/shot2.jpg
    alt: 关系标注
---

> 面向遥感影像的**对象—关系**结构化标注与质检工具，支持导出训练集并与检索/建模联动。

### 关键信息
<div class="tags">
  <span class="tag blue">Python</span>
  <span class="tag purple">PyQt</span>
  <span class="tag indigo">CV</span>
  <span class="tag teal">遥感</span>
  <span class="tag green">GIS</span>
</div>

## 概览
- 标注 **对象/谓词/关系**，内置一致性校验与批量质检  
- 导出 COCO/自定义格式；与检索/训练管线对接  
- 配套**使用手册**与**软著**

## 职责与贡献
- 0→1 设计标注流程、类目体系与质检机制  
- 开发 GSGA 工具与**半自动标注**模块（提升效率）  
- 组织生产 **15k 对象 + 12.5k 关系** 的高质量数据

## 技术栈
Python、PyQt、OpenCV、Shapely、COCO API

## 关键结果
- 标注准确率 **97%+**，类目分布更均衡  
- 手动标注平均时长 **↓1.5 分钟/100 张**，错误率 **↓15%**

## 截图
{% include gallery %}

## 资源
[GitHub](https://github.com/YourRepo){: .btn .btn--primary } 
[下载手册](/assets/docs/gsga.pdf){: .btn } 
[返回科研页]({{ '/research/' | relative_url }}){: .btn }
