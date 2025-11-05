---
layout: page
title: Tensor Networks and Their Application to Supervised Learning Tasks
description: Institute of Physics, Academia Sinica, Taipei, Taiwan 
#img: assets/img/7.jpg
#redirect: https://unsplash.com
importance: 3
category: research-related
---

Mentor: [Dr. Hong-Yan Shih](https://www.phys.sinica.edu.tw/~hongyan/){: .link-chip }, [Prof. Yi-Ping Huang](https://scholar.google.com/citations?user=bUAikIoAAAAJ&hl=zh-TW){: .link-chip }, Dr. Valentin Anfray

[detailed_report](/assets/pdf/10_page_report.pdf){: .link-chip }


{: .text-justify}
In the summer after my sophomore year, I joined the undergraduate research internship at the Institute of Physics, Academia Sinica. I explored the application of Tensor Networks (TN) from quantum physics to enhance machine learning interpretability. My work was largely self-directed, in collaboration with Dr. Shih, who is from outside the ML field. 

{: .text-justify}
Applying a Matrix Product State (MPS) model to the MNIST dataset is challenging, since MPS was not designed for visual types of data. With the guidance of my mentors, I switched my attention to a "finding-global-maximum" task. This allowed me to test the learning algorithm, the Density Matrix Renormalization Group (DMRG), which used tensor network systems. This algorithm was originally proposed by 
[Edwin Miles Stoudenmire](https://scholar.google.com/citations?user=DLFxevAAAAAJ&hl=en){: .link-chip }, who is a renowned researcher exploring the potential of tensor networks!!


<div class="row">
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/project3_poster.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-2 mt-md-1">
        {% include figure.liquid loading="eager" path="assets/img/projects/project3_mewiththelab.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    
</div>
<div class="caption">
    It is my poster for the final presentation on the left. Right, is the group photo of me and everyone in my lab.
</div>

{: .text-justify}
The model achieved 98% accuracy on our toy dataset, and my mentor and I noticed a mismatch here. The MPS architecture has a natural strength in capturing local correlations, while the task focuses on capturing global information. (The goal of the task is to find the global max!!) The algorithm still works fine, but it would need extra storage space, which is not ideal and needs further exploration.

{: .text-justify}
At the end of my internship, I joined the poster session and shared my findings with the whole physics institute.


### Reference
[1] Stoudenmire, E., & Schwab, D. J. (2016). Supervised learning with tensor networks. Advances in neural information processing systems, 29.

