---
layout: page
title: An Automated Alarm System with Sleep Detection Implementation
description: EE4057 Electrical Engineering Lab (Biomedical Engineering), National Taiwan University, Taipei, Taiwan
#img: assets/img/1.jpg
importance: 3
category: industry-related
---


[Demo video link](https://youtu.be/zepfCfav4Hw){: .link-chip } | 
[GitHub Repo](https://github.com/yuehhsuanhuang/2024Fall-Bio-Lab-Final-Project){: .link-chip }


{: .text-justify}
I was responsible for implementing the signal processing step for a smart alarm prototype. This alarm allows dynamically adjusting the wake-up time with the detection of a true sleep onset. Our system addresses the failure of common apps by using precise EEG data instead of unreliable microphone audio.


{: .text-justify}
My primary task was translating raw, noisy EEG data into a reliable sleep marker. I first used a Python preprocessing filter to denoise the EEG data. Then, I applied bandpass filtering and Morlet wavelet convolution to precisely identify sleep spindles, a key indicator of entering Stage 2 sleep.


{: .text-justify}
This processing engine was linked with an EEG sensor, an Arduino controller, and a user-facing app. Our full-stack prototype, demonstrated via real-time simulation, proved the concept’s viability for a more natural and smooth sleep experience.



<div class="row">
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/project5_morletwave.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-2 mt-md-1">
        {% include figure.liquid loading="eager" path="assets/img/projects/project5_spindleexample.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    
</div>
<div class="caption">
    On the left, there is the morlet wave. On the right, the red regions represent detected spindles.
</div>




