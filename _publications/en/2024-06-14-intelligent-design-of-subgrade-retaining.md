---
title: "Intelligent Design Method of Subgrade Retaining based on Bentley"
lang: en
ref: publications/2024-06-14-intelligent-design-of-subgrade-retaining
collection: publications
permalink: /en/publications/2024-06-14-intelligent-design-of-subgrade-retaining
excerpt: 'This study proses an intelligent approach to automatically generate design model and drawing of subgrade retaining in the road engineering area.'
date: 2024-06-14
venue: 'Journal of Tsinghua University (Science & Technology)'
doi: '10.16511/j.cnki.qhdxxb.2024.26.039'
paperurl: 'https://link.cnki.net/doi/10.16511/j.cnki.qhdxxb.2024.26.039'
citation: 'Tang, H.W., Geng, X.Y., Chen, H.T., Tan, H.C., Zeng, F.Y., Lin, J.R.* (2024). Intelligent Design Method of Subgrade Retaining based on Bentley. <i>Journal of Tsinghua University (Science & Technology)</i>, 64(9), 1627-1636. doi: 10.16511/j.cnki.qhdxxb.2024.26.039'

comment: true
category: journal

tags: 
  - intelligent design
  - BIM
  - road engineering
  - subgrade retaining
  - generative design
  - EI

grants:
  - 72091512
  - 52378306
---


{{site.data.ui-text[page.lang].abstract}}
====

[Objective] With the rapid development of informatization and digitization, it has become challenging for traditional 2D design methods to meet the requirements of tight time limitations and lifecycle modeling management. In addition, the manual assignment of model properties is complicated and time-consuming for designers. To improve the inefficiency and inconvenience of manual retaining design and to enrich incomplete information generated using existing BIM software. 

[Methods] This paper summarizes the boundary condition and process of deploying retaining according to specification and studies the delivery requirements of BIM information and the challenges of traditional design software. Then, an intelligent algorithm for deploying a retaining wall is proposed, with which the condition for placing the retaining wall can be checked at each station along the path. The automatic matching of retaining types and heights, bottom slope smoothing, and merging of different segments are also achieved. A retaining software plug-in is redeveloped based on the OpenRoads Designer of the Bentley platform for validation and application. National standard drawings and subgrade retaining structures are embedded in the system, guaranteeing the structural security of the wall. The continuous highway is discretized into station sequence, and a dichotomy is used to rapidly find the most suitable height on each section, considering the flap width and buried depth requirements. To optimize the construction cost, the location of the retaining wall is filtered by the side slope height along the highway. Various types of retaining walls contained in the software can be selected by custom priority. The subgrade retaining walls are divided into different parts based on length and bottom slope restriction. The bottom edges of the generated segments are finally readjusted to a linear or stair-stepping state, and the height of each section is recalculated based on the measurements. Thus, the one-click intelligent design of subgrade retaining is completed. [Results] Several products were obtained by the system, which were summarized as follows: (1) plan, elevation, and cross-section drawings of each retaining segment, including graphic shapes and size dimensions; (2) engineering quantity sheets containing detailed items; (3) 3D retaining models attached with information in the level of details 3.0. The output provided accurate results, fulfilled industrial requirements, and could be further used in construction, operation, and maintenance process management. The method was validated by a practical highway project with a length of 13.4 km. The comparisons of the results with HintCAD (a popularly used software on highways) were summarized as follows: (1) deviation was less than 6% on the total retaining length, gravel inverted filter layer, geotextile, and earthwork volume owing to the ignorance of geology and environmentally sensitive areas and terrain-calculation difference between 2D and 3D methods. (2) The error of average retaining height and concrete volume is less than 12%, which was caused by manual and conservative bottom handling methods. (3) The precision accuracy was completely accepted table for engineering projects in the preliminary design stage. (4) The calculated results could be further modified by users to fulfill the design intent. 

[Conclusions] Thus, this method offers a better option for retaining design and deployment and considerably improves design efficiency, 3D visualization, and property information compared with the current design approach, which contributes to 3D forward design in railway and highway projects.

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2024-06-14-intelligent-design-of-subgrade-retaining.pdf)

The authors are grateful for the financial support received from the National Natural Science Foundation of China (No. 72091512, No. 52378306). 