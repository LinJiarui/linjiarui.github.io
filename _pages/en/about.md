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
  - url: /en/posts/2023-09-24-winner-of-buildingSMART-openBIM-awards
    image_path: 2023-09-24-winner-of-buildingSMART-openBIM-awards.jpg
    title: "Winner in 2023 buildingSMART openBIM Awards"
    excerpt: "We are the winner in the category of professional research of bSI OpenBIM Awards 2023"
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

Dr. Jia-Rui Lin is currently an associate professor at the Disaster Prevention and Mitigation Institute of Tsinghua University, and concurrently the director of the Mechanics Computing and Simulation Laboratory of the Mechanics Experimental Teaching Center of Tsinghua University. Dr. Lin obtained his bachelor's degree (2011) and Ph.D. (2016) from the Department of Civil Engineering of Tsinghua University. After finished his postdoctoral research in 2018, he joined the Department of Civil Engineering, Tsinghua University as a faculty member. Dr. Lin was also visiting scholars of Stanford University, RWTH-Aachen University and University of Southern California.

His research interests are information technology for building and civil engineering, including smart/intellignet construction, building information model (BIM), domain specific large language models, and robotics. Recently, he was granted by the national natural science foundation, national key R&D program, Beijing natural science foundation, etc. for more than 20 projects, and has co-authored more than 130 peer-reviewed journal and conference papers, 6 book chapters. He also holds more than 30 patents and software copyrights. 

In 2016, he was selected as a receiver of Young Elite Scientists Sponsorship Program by the China Association for Science and Technology. In 2023, his team is the winner of the buildingSMART openBIM Award in the category of professional research. He also won many prizes such as the Grand Prize of the Science and Technology Award of the Yellow River Conservancy Commission), the second prize of the China Construction Science and Technology Award. Dr. Lin also won the first prize of 8th Teaching Competition for Young Faculties in Tsinghua and the third prize of the 11th Teaching Competition for Young Faculties in Beijing in 2018 and 2019 respectively.

Dr. Lin serves as the council member of China Graphics Society (CGS), the general secretary of Professional Committee for Building Information Modeling of CSG, and also is the editorial member of [Journal of Graphics](http://www.txxb.com.cn/CN/2095-302X/home.shtml), [Buildings](https://www.mdpi.com/journal/buildings), etc. 

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
