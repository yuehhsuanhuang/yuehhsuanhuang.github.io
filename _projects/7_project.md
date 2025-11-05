---
layout: page
title: AI-Powered News Rundown Automation
description: TVBS Media Inc., Taipei, Taiwan
#img: assets/img/4.jpg
importance: 1
category: industry-related
#related_publications: true
---
***due to NDA, there is no demo link to the website***

{: .text-justify}
As an AI Intern at [TVBS](https://www.tvbs.com.tw/){: .link-chip }, Taiwan's leading media network, I was one of the main developers on a project to automate the news rundown workflow. 
(A rundown refers to the order of news items scheduled for a particular broadcast period, which is usually a 1-hour segment.)


{: .text-justify}
The system's primary goal was to translate a 20-year veteran editor's expertise into a scalable workflow using n8n and Google Gemini. The pipeline successfully reduces the required editorial review time from 20 minutes to just 5 minutes — a 75% efficiency gain. (A feedback from an ex-editor coworker.) The project now processes over 2,000 articles monthly.


<div class="row">
    <div class="col-sm mt-1 mt-md-0">
 {% include figure.liquid loading="eager" path="assets/img/projects/project7_rdfrontend.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
 This image demonstrates the front-end website for rundown checking and editing. 
</div>

{: .text-justify}
Additionally, one of my key contributions was implementing a data pipeline to integrate Google Trends keywords. The default RSS link previously used often scrapes non-related keywords. I overcame this challenge by combining Google Cloud Platform and the open source Python module trendspy. This single improvement boosted the system's identification of hot topics by over 10x, directly enhancing the quality of data-driven rundown ordering.


{: .text-justify}
My current prototype allows editors to specify only high-level editorial directions, while LLMs generate the final rundown based on these prompts. This design improves flexibility and simplifies maintenance. It also shifts news scheduling from manual experience to the teamwork between humans and AI, introducing new possibilities for newsroom collaboration.




