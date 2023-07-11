---
permalink: /en/
title: "About me"
lang: en
ref: about
excerpt: "About me"
author_profile: true
redirect_from: 
  - /en/about/
  - /en/about.html

slideshow:
  - url: /en/posts/2022-08-05-call-for-paper-3D-CV-and-BIM
    image_path: 2022-08-05-call-for-paper-3D-BIM-ga.jpg
    title: "Call for Papers: 3D CV and Smart Building/City"
    excerpt: "Multiple SCI-indexed journals are involved, submission before April 30, 2023"
  - url: /en/publications/2022-03-11-how-human-robot-collaboration-impacts-construction-productivity
    image_path: 2022-03-11-how-human-robot-collaboration-impacts-construction-productivity-ga.jpg
    title: "Human-Robot Collaboration and its Impact on Productivity"
    excerpt: "A multi-fidelity modeling approach is proposed, which shows the complexity of HRC"
  - url: /en/publications/2021-10-03-best-practices-of-ifc-based-ARC-case-study
    image_path: 2021-10-03-best-practices-of-ifc-based-ARC-case-study-ga.jpg
    title: "Best Practice for Automatic Compliance Checking"
    excerpt: "A framework for proactive ARC is proposed, which chould interactively generate design suggestions based on ARC"
  - url: /en/publications/2021-10-30-fireload-recognition-based-on-mask-rcnn
    image_path: 2021-10-30-fireload-recognition-based-on-mask-rcnn-all.jpg
    title: "Fire Load Recognition based on Deep Learning"
    excerpt: "Mask-RCNN based indoor fire load recognition method and open dataset are developed"
---

Dr. Jia-Rui Lin is currently a research assistant professor at the Disaster Prevention and Mitigation Institute of Tsinghua University, and concurrently the director of the Mechanics Computing and Simulation Laboratory of the Mechanics Experimental Teaching Center of Tsinghua University. He also serves as the general secretary of Professional Committee for Building Information Modeling, China Graphics Society. Dr. Lin obtained his bachelor's degree (2011) and Ph.D. (2016) from the Department of Civil Engineering of Tsinghua University. After finished his postdoctoral research in 2018, he joined the Department of Civil Engineering, Tsinghua University as a faculty member. Dr. Lin was also visiting scholars of Stanford University, RWTH-Aachen University and University of Southern California.

His research interests are information technology for building and civil engineering, including smart/intellignet construction, building information model (BIM), augmented reality (AR) ,cloud computing and internet of things (IoT). He is committed to optimizing performance and improving decision-making process in the construction, operation, maintenance, and disaster prevention of buildings and infrastructures through advanced information technology. In 2016, he was selected as a receiver of Young Elite Scientists Sponsorship Program by the China Association for Science and Technology. At the end of 2018, Dr. Lin was awarded the second prize of the China Construction Science and Technology Award and the third prize of Beijing Science and Technology Award. Recently, He was awarded the second prize of Science and Technology Award of Shanghai Society of Civil Engineering. Dr. Lin also won the first prize of 8th Teaching Competition for Young Faculties in Tsinghua and the third prize of the 11th Teaching Competition for Young Faculties in Beijing in 2018 and 2019 respectively.

Recently, he was granted by the national natural science foundation, national key R&D program, Beijing natural science foundation, etc. for more than 20 projects, and has co-authored more than 100 peer-reviewed journal and conference papers, 4 book chapters. He also holds more than 20 software copyrights. 

## Join Us
Our group welcome application for research assistant, postdoctoral fellow in the field of construction informatics, civil engineering, please email me for detail with your CV (email address could be found at the end of this page).

{% include base_path %}

{% include slideshow %}

## News
{% assign posts = site.posts | where:"lang", page.lang %}
{% assign posts = posts | sort: 'date' %}
{% assign posts = posts | reverse %}
<ul>{% for post in posts limit:3 %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

[Find More>>]({{ site.baseurl }}/{{page.lang}}/year-archive/)
## Recent Publications
{% assign publications = site.publications | where:"lang", page.lang %}
{% assign publications = publications | reverse %}
<ul>{% for post in publications limit:4 %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

[Find More>>]({{ site.baseurl }}/{{page.lang}}/publications/)
## Recent Talks
{% assign talks = site.talks | where:"lang", page.lang %}
{% assign talks = talks | reverse %}
<ul>{% for post in talks limit:2 %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

[Find More>>]({{ site.baseurl }}/{{page.lang}}/talks/)
## Recent Projects
{% assign projects = site.projects | where:"lang", page.lang %}
{% assign projects = projects | reverse %}
<ul>{% for post in projects limit:2 %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

[Find More>>]({{ site.baseurl }}/{{page.lang}}/projects/)
## Recent Teaching Activities
{% assign teaching = site.teaching | where:"lang", page.lang %}
{% assign teaching = teaching | reverse %}
<ul>{% for post in teaching limit:2 %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

[Find More>>]({{ site.baseurl }}/{{page.lang}}/teaching/)
## Contact me
TEL:86-10-62789225
E-mail: lin611(AT)tsinghua.edu.cn (replace `AT` with `@`)
