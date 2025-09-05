---
layout: page
title: Tensor Networks and Their Application to Supervised Learning Tasks
description: Institute of Physics, Academia Sinica, Taipei, Taiwan 
#img: assets/img/7.jpg
#redirect: https://unsplash.com
importance: 3
category: research-related
---

Mentor: [Dr. Hong-Yan Shih](https://www.phys.sinica.edu.tw/~hongyan/), [Prof. Yi-Ping Huang](https://scholar.google.com/citations?user=bUAikIoAAAAJ&hl=zh-TW), Dr. Valentin Anfray


In the summer after my sophomore year, I joined the undergraduate research internship at Academia Sinica's Institute of Physics. I explored the novel application of Tensor Networks (TN) from quantum physics to enhance machine learning interpretability. My work was largely self-directed, in a collaborative exploration with an advisor from outside the ML field. 


Applying a Matrix Product State (MPS) model to the MNIST dataset is challenging, for the different nature of MPS and visual types of data. With the guidance of my mentors, I switched my attention to a "finding-global-maximum" task. This allowed me to rigorously test the learning algorithm, which was inspired by the Density Matrix Renormalization Group (DMRG) used in researcher [Edwin Miles Stoudenmire's](https://scholar.google.com/citations?user=DLFxevAAAAAJ&hl=en) work.

I achieved 98% accuracy on our toy dataset, and my mentor and I noticed a fundamental mismatch between the MPS architecture’s strength in capturing local correlations and the task's need for global information. At the end of my internship, I joined the poster session and share my findings with the whole physics institute.





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



### Reference
[1] Stoudenmire, E., & Schwab, D. J. (2016). Supervised learning with tensor networks. Advances in neural information processing systems, 29.

