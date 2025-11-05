---
layout: page
title: Parameter-Efficient Transfer Learning for Multi-Modal Sequential Recommendation
description: Interdisciplinary Data Science & Signal Processing Lab, National Taiwan University, Taipei, Taiwan 
#img: assets/img/12.jpg
importance: 1
category: research-related
related_publications: false
---

Mentor: [Prof. Che Lin](https://www.ee.ntu.edu.tw/profile1.php?teacher_id=25203){: .link-chip }

{: .text-justify}
This project aims to address the efficiency bottleneck faced by multimodal recommendation model -- [MTSTRec](https://icml.cc/virtual/2025/poster/43526){: .link-chip }. Although MTSTRec is powerful, its training cycle can take nearly a full day on larger datasets, making it challenging for rapid adaptation to other datasets. The demand for rapid adaptation stems from the various shopping scenarios commonly encountered in real-world recommendation cases.

{: .text-justify}
The core of my research is to explore how to use parameter-efficient fine-tuning (PEFT) techniques, such as LoRA and Adapter, to speed up the fine-tuning process while maintaining test performance. The overall time bottleneck of MTSTRec is the process of generating high-quality product embeddings. Currently, my work is focused on this aspect, and due to GPU constraints, I am re-implementing MTSTRec using Gemma to maintain efficiency under limited computational resources.

The next steps would be a more thorough discussion on different PEFT methods.

#### Reference
[1] Hong, M. Y., Hsu, Y. J., Chiang, M. C., & Lin, C. MTSTRec: Multimodal Time-Aligned Shared Token Recommender. In Forty-second International Conference on Machine Learning.
