---
title: On Evaluating Adversarial Robustness of Volumetric Medical Segmentation Models
authors:
- Hashmat Shadab Malik
- Numan Saeed
- Asif Hanif
- Muzammal Naseer
- Mohammad Yaqub
- Salman Khan
- Fahad Shahbaz Khan
date: '2024-09-01'
publishDate: '2024-10-13T06:34:23.558354Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2406.08486
abstract: Volumetric medical segmentation models have achieved significant success
  on organ and tumor-based segmentation tasks in recent years. However, their vulnerability
  to adversarial attacks remains largely unexplored, raising serious concerns regarding
  the real-world deployment of tools employing such models in the healthcare sector.
  This underscores the importance of investigating the robustness of existing models.
  In this context, our work aims to empirically examine the adversarial robustness
  across current volumetric segmentation architectures, encompassing Convolutional,
  Transformer, and Mamba-based models. We extend this investigation across four volumetric
  segmentation datasets, evaluating robustness under both white box and black box
  adversarial attacks. Overall, we observe that while both pixel and frequency-based
  attacks perform reasonably well under emphwhite box setting, the latter performs
  significantly better under transfer-based black box attacks. Across our experiments,
  we observe transformer-based models show higher robustness than convolution-based
  models with Mamba-based models being the most vulnerable. Additionally, we show
  that large-scale training of volumetric segmentation models improves the model's
  robustness against adversarial attacks. The code and robust models are available
  at 
  https://github.com/HashmatShadab/Robustness-of-Volumetric-Medical-Segmentation-Models.
tags:
- Computer Science - Computer Vision and Pattern Recognition
- Electrical Engineering and Systems Science - Image and Video Processing
links:
- name: URL
  url: http://arxiv.org/abs/2406.08486
---
