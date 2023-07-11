---
permalink: /
title: "个人简介"
lang: zh
ref: about
excerpt: "关于我"
author_profile: true
redirect_from: 
  - /about/
  - /about.html

slideshow:
  - url: /posts/2022-08-05-call-for-paper-3D-CV-and-BIM
    image_path: 2022-08-05-call-for-paper-3D-BIM-ga.jpg
    title: "3D计算机视觉及智慧建筑/城市论文征稿"
    excerpt: "Drones，Sustainability，Sensors，Buildings，Energies多期刊支持，2023/4/30截止"
  - url: /publications/2022-03-11-how-human-robot-collaboration-impacts-construction-productivity
    image_path: 2022-03-11-how-human-robot-collaboration-impacts-construction-productivity-ga.jpg
    title: "人机协同建造过程仿真论文已在AEI发表"
    excerpt: "建立人机协同建造多尺度仿真模型，探索了人机协同对施工效率的影响"
  - url: /publications/2021-10-03-best-practices-of-ifc-based-ARC-case-study
    image_path: 2021-10-03-best-practices-of-ifc-based-ARC-case-study-ga.jpg
    title: "智能审图最佳实践论文已发表"
    excerpt: "研究提出考虑用户需求的主动式审图框架，可动态输出设计参数取值建议"
    #只支持四个图片轮转
  - url: /publications/2021-10-30-fireload-recognition-based-on-mask-rcnn
    image_path: 2021-10-30-fireload-recognition-based-on-mask-rcnn-all.jpg
    title: "火荷载自动识别的论文已发表"
    excerpt: "研究构建了首个室内火荷载标注数据集及深度学习识别算法"
---

林佳瑞，现任清华大学土木系防灾减灾所助理研究员，兼任清华大学力学实验教学中心力学计算与仿真实验室主任、土木工程暨建设管理系研工组组长以及中国图学学会理事、BIM专委会秘书长等职务。先后于清华大学土木系获得学士（2011年）、博士学位（2016年），2018年博士后出站后加入清华大学土木系。斯坦福大学、亚琛工业大学、南加州大学访问学者。

主要研究方向为智能建造、BIM/CIM与数字防灾技术，致力于通过先进信息技术提升工程建造、管理及防灾过程的自动化与科学决策水平。获得2016-2018年度中国科协“青年人才托举工程”资助，获得2018年华夏建设科学技术二等奖、2018年北京市科学技术三等奖、2021年上海市土木学会科技进步二等奖、2022年中国图学学会科技进步一等奖以及2018年清华大学青年教师教学大赛一等奖、2019年北京市高校青年教师教学基本功大赛三等奖、2023年清华大学第十八届“良师益友”等荣誉。

近年来，主持和承担国家自然科学基金、重点研发计划、863计划、北京市自然科学基金等研究课题20余项，在国内外学术刊物和会议发表相关论文100余篇，参编地标、行标4部，参编专著4部，申请专利、软件著作权20余项。

## 加入我们
本课题组长期招收研究助理、研究生或博士后，欢迎感兴趣的同学联系我（联系方式见本页末尾），来信请简单自我介绍并附简历。

{% include base_path %}

{% include slideshow %}

## 新闻
{% assign posts = site.posts | where:"lang", page.lang %}
{% assign posts = posts | sort: 'date' %}
{% assign posts = posts | reverse %}
<ul>{% for post in posts limit:3 %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

[查看全部>>]({{ site.baseurl }}/year-archive/)
## 近期论文
{% assign publications = site.publications | where:"lang", page.lang %}
{% assign publications = publications | reverse %}
<ul>{% for post in publications limit:4 %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

[查看全部>>]({{ site.baseurl }}/publications/)
## 近期报告
{% assign talks = site.talks | where:"lang", page.lang %}
{% assign talks = talks | reverse %}
<ul>{% for post in talks limit:2 %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

[查看全部>>]({{ site.baseurl }}/talks/)
## 近期项目
{% assign projects = site.projects | where:"lang", page.lang %}
{% assign projects = projects | reverse %}
<ul>{% for post in projects limit:2 %}
  {% include archive-single-cv.html %}

{% endfor %}</ul>

[查看全部>>]({{ site.baseurl }}/projects/)
## 近期教学
{% assign teaching = site.teaching | where:"lang", page.lang %}
{% assign teaching = teaching | reverse %}
<ul>{% for post in teaching limit:2 %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

[查看全部>>]({{ site.baseurl }}/teaching/)
## 联系方式
电话：(010)62789225
邮箱：lin611(AT)tsinghua.edu.cn (请将`AT`替换为`@`)

## 内容转载
本站主要介绍本人团队及课题组有关工作，有关内容多为课题组原创成果，请勿用于任何商业目的，如需转载相关内容请与我联系。