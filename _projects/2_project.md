---
layout: page
title: Implement human face recognition and character verification by image processing techniques
description: Digital Image and Signal Processing Lab, National Taiwan University  
#img: assets/img/3.jpg
importance: 2
category: research-related


---
Mentor: [Prof. Jian-Jiun Ding](https://www.ee.ntu.edu.tw/profile1.php?teacher_id=942019)


I implemented two distinct verification systems to build hands-on skills in Python, image processing, and classical machine learning.

For face detection, I realized a multi-stage pipeline. The process began by segmenting skin-tone pixels with a custom-trained SVM, followed by ellipse fitting to isolate potential face regions. Convolutional methods were then employed to generate eye and mouth maps for eye & mouth detection. By enforcing strict geometric consistency rules, the system achieved a flawless **1.0 precision and a 0.955 F1-score on our private dataset with 80+ pictures.**

For signature verification, I trained a SVM classifier by experimenting with different feature combination. These features quantified zonal pixel density and the geometric relationships between stroke inflection points, enabling the model to achieve **88% accuracy in distinguishing between 1,000 genuine and forged samples.** 



<div class="row">
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/project2_skinsvm.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-2 mt-md-1">
        {% include figure.liquid loading="eager" path="assets/img/projects/project2_mouthmap.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    
</div>
<div class="caption">
    On the left, white regions mean detected skin areas, while black regions mean non-skin areas. On the right, the red dots show possible positions of mouth.  
</div>




<div class="row">
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/project2_differentfeature.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-2 mt-md-1">
        {% include figure.liquid loading="eager" path="assets/img/projects/project2_findingspecialpoints.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    
</div>
<div class="caption">
    On the left, the picture is divided into 5 regions, horizontally and vertically. Two types of features could be found by counting the number of colored points in each region. On the right, the blue dots show the turns in the handwriting. 
</div>


