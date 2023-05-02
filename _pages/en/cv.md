---
layout: archive
lang: en
ref: cv
title: "Curriculum Vitae"
permalink: /en/cv/
author_profile: true
redirect_from:
  - /en/resume
---

{% include base_path %}
{% include toc icon="cog" title="Contents" %}

## Education
* Aug, 2011-Jun, 2016: Ph.D in Department of Civil Engineering, Tsinghua University
* Aug, 2007-Jul, 2011: B.S. in Department of Civil Engineering, Tsinghua University

## Work experience
* July, 2020-Now: Leader of Working Group for Graduate Affairs at Department of Civil Engineering, Tsinghua University
* Dec, 2018-Now: Director of the Mechanics Computing and Simulation Laboratory, Tsinghua University
* Aug, 2018-Now: Research Assistant Professor, Tsinghua University
* Jul, 2016-Aug, 2018: Postdoctoral Research Associate, Tsinghua University
  * Research area: Maintenance of buildings and infrastructures based on BIM and IoT
  * Mentor: Professor Jian-Ping Zhang
* Jan, 2018-Jun, 2018: Visiting Scholar, Stanford University
* Nov, 2016-Dec, 2016: Visiting Scholar, RWTH-Aachen University
* Aug, 2011-Jun, 2016: Research Assistant, Tsinghua University
  * Research area: Building Information Modeling and Building Lifecycle Management
  * Supervisor: Professor Jian-Ping Zhang
* Jul, 2015-Aug, 2015: Visiting Scholar, University of Southern  California
* Jul, 2010-Sept, 2010: Structural Engineer Internship, Singapore CPG Co. Ltd.

## Honors&Awards
### Research
* Jan, 2022, First Prize of the 2021 Science and Technology Award of the China Graphics Society (rank 5/14)
* May, 2021, Second Prize of the 2021 Science and Technology Award of Shanghai Society of Civil Engineering (rank 2/9)
* Jan, 2019, Second Prize of the 2018 China Construction Science and Technology Award (rank 3/12)
* Nov, 2018, Third Prize of the 2018 Beijing Science and Technology Award (rank 4/6)
* Oct, 2016, Young Elite Scientists Sponsorship Program by the China Association for Science and Technology
* Oct, 2016, RWTH Aachen – Tsinghua Senior Research Fellowship
* Dec, 2022, Best Paper Award of the 2022 International Conference on Construction and Real Estate Managenent (ICCREM 2022)
* Oct, 2021, Best Paper Award of the 2021 International Conference on Construction and Real Estate Managenent (ICCREM 2021)
* Dec, 2020, Best Paper Award of the 8th International Conference on Innovative Production and Construction (IPC 2020)
* Nov, 2020, Best Paper Award of 6th National Conference on Building Information Modeling
* Jan, 2019, Best Paper Award of _Journal of Graphics_
* Nov, 2018, Best Paper Award of 4th National Conference on Building Information Modeling
* Nov, 2014, Best Paper of 17th Conference on Computing in Civil Engineering in China
* Nov, 2014, Best Presentation of Tsinghua University Doctoral Academic Forum

### Teaching
* Dec, 2022, Great Mentor and Beneficial Friend selected by the graduate students in Tsinghua (47 in total)
* Oct, 2022, Excellent Instructor for Social Practice of Tsinghua (20 in total)
* Jun, 2022, Excellent Advisor for Graduate Students of Tsinghua
* Jun, 2022, the Most Popular Instructor selected by the students graduated this year
* Jun, 2022, _Data Science_ (the course I teach) was selected as the Best Course by the students graduated this year
* May, 2022, Receiver of the LuQian Incentive Scholarship for Learning and Teaching of Department of Civil Engineering and Construction Management of Tsinghua University
* Dec, 2021, Outstanding Faculty for the Career Guidance of Graduate Students in Tsinghua (35 in total)
* Dec, 2020, Excellent Advisor of the Tsinghua "12.9" Graduate Student Chorus
* Dec, 2020, Excellent Advisor (First Prize) of the 2020 Student Research Trainning Program of Tsinghua University (15 in total)
* Jul, 2020, Excellence Award of Tsinghua University for Online Teaching during the COVID-19 Pandemic
* Dec, 2019, Excellent Advisor (First Prize) of the 2019 Student Research Trainning Program of Tsinghua University (15 in total)
* Jul, 2019, Third Prize of the 11th Teaching Competition for Young Faculties in Beijing
* Dec, 2018, First Prize of 8th Teaching Competition for Young Faculties in Tsinghua
* Oct, 2017, Second Prize of Teaching Competition in School of Civil Engineering
* Dec, 2014, Tsinghua "12.9" Graduate Assistant Award
* Aug, 2012, Best Teaching Assistant in School of Civil Engineering, Tsinghua

### Services
* Jul, 2021, Outstanding Service Award of the 7th Council of China Graphics Society

### Competition
* Jul, 2022, Grand Prize, Second Prize, and Third Prize of the 4th "Maoyisheng Charity Bridge" Innovative Design Competition
* Jan, 2022, Grand Prize of the 3rd "Gongchuang Cup" Competition for Intelligent Construction
* Nov, 2021, First Prize of the Future Space Competition of Longfor

### Practice
* Apr, 2016, First Prize of the 4th "Longtu Cup" National Building Information Model (BIM) Competition
* Dec, 2015, Excellence Project Award of the China Construction Industry Association
* May, 2014, First Prize of the 4th "Longtu Cup" National Building Information Model (BIM) Competition

### Education
* Nov, 2015, Excellent Scholarship for Graduates in Tsinghua
* Jul, 2011, Outstanding Undergraduates of Tsinghua University and the Beijing City
* Dec, 2010, Rising Star of Science & Innovation (undergraduate) in Tsinghua, candidate for the Special Scholarship of Tsinghua (Top 10 in the university)
* Dec, 2009, First Prize of the 15th Structure Design Competition in Tsinghua
* Oct, 2009, Academic Gold Medal from School of Aerospace Engineering in Tsinghua
* Aug, 2009, Special Award of the 7th National Zhou Peiyuan Mechanics Competition for College Students

## Publications
{% assign publications = site.publications | where:"lang", page.lang %}
{% assign journals = publications | where:"category", 'journal' %}
{% assign proceedings = publications | where:"category", 'conference' %}
{% assign books = publications | where:"category", 'book' %}
{% assign chapters = publications | where:"category", 'chapter' %}
  
{% if journals.size>0 %}
### Journal Publications
  <ul>{% for post in journals reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
{% endif %}
{% if proceedings.size>0 %}
### Conference Publications
  <ul>{% for post in proceedings reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
{% endif %}
{% if books.size>0 %}
### Books
  <ul>{% for post in books reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
{% endif %}
{% if chapters.size>0 %}
### Book Chapters
  <ul>{% for post in chapters reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
{% endif %}
  
## Talks
{% assign talks = site.talks | where:"lang", page.lang %}
<ul>{% for post in talks reversed%}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

## Research Projects
{% assign projects = site.projects | where:"lang", page.lang %}
{% assign from_govs = projects | where:"sponsor", 'government' %}
{% assign from_comps = projects | where:"sponsor", 'company' %}
### Funded by Government
<ul>{% for post in from_govs reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
### Sponsored by Companies
<ul>{% for post in from_comps reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
  
## Teaching
{% assign teaching = site.teaching | where:"lang", page.lang %}
<ul>{% for post in teaching reversed%}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
   
## Service and Leadership
* July, 2021-Now: General Secretary of Professional Committee for Building Information Modeling, China Graphics Society
* July, 2021-Now: Council Member of China Graphics Society
* July, 2021-Now: Member of Working Committee for Youth Development, China Graphics Society
* Jan, 2023-Now: Editorial Board Member of _Buildings_
* July, 2021-Now: Academic Editor of _Advances in Civil Engineering_
* November, 2016-Now: Member of Professional Committee for Building Information Modeling, China Graphics Society
* August, 2019-Now: Special Expert of building information modeling center of Beijing City Planning Society
### Guest Editors
* Topic Editor of "3D Computer Vision and Building Information Modeling" (2022-2024), _Drones_, _Sensors_, _Sustainability_, _Buildings_, _Energies_
* Lead Guest Editor of "Smart Sensing in Building and Construction" (2021), _Sensors_
* Guest Editor of "Intelligent and Computer Technologies Application in Construction II" (2022-2023), _Buildings_
* Guest Editor of "Intelligent and Computer Technologies Application in Construction" (2021-2022), _Buildings_
* Guest Editor of "Smart and Resilient Infrastructure based on AI and Digital Twin" (2021-2022), _Advances in Civil Engineering_
* Guest Editor of "Digital Twin in the Architectural, Engineering and Construction (AEC) Industry" (2019-2020), _Advances in Civil Engineering_
### Reviewers
* _Automation in Construction_
* _Journal of Computing in Civil Engineering_
* _Journal of Construction Engineering and Management_
* _IEEE Transactions on Systems, Man and Cybernetics: Systems_
* _Archives of Computational Methods in Engineering_
* _Artificial Intelligence Review_
* _Advanced Engineering Informatics_
* _Tunnelling and Underground Space Technology_
* _Remote Sensing_
* _Journal of Management in Engineering_
* _Energy Reports_
* _Engineering, Construction and Architectural Management_
* _IEEE Access_
* _Sensors_
* _Applied Sciences_
* _Safety_
* _Mobile Information Systems_
* _Advances in Structural Engineering_
* _Advances in Civil Engineering_
* _Canadian Journal of Civil Engineering_
* _Journal of Advanced Transportation_
* _Journal of Environmental and Public Health_
* _Mathematical Problems in Engineering_
* _Journal of Structural Integrity and Maintenance_
* _Frontiers of Engineering Management_
* _Energy and Built Environment_
* _Proceedings of the Institution of Civil Engineers - Smart Infrastructure and Construction_
* _International Journal of Construction Management_
* _Journal of Tsinghua University (Science & Technology)_
* _China Civil Engineering Journal_
* _Engineering Mechanics_
* _China Journal of Highway and Transport_
* _Journal of Graphics_
* _Construction Technology_
* _Journal of Information Technology in Civil Engineering and Architecture_
