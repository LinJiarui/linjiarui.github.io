---
layout: archive
title: "网站地图"
lang: zh
ref: sitemap
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

本站所有页面列表如下，用于网络爬虫的XML版本[在这]({{ base_path }}/sitemap.xml)。

<h2>页面</h2>
{% assign pages = site.pages | where:"lang", page.lang %}
{% for post in pages %}
  {% include archive-single.html %}
{% endfor %}

<h2>新闻动态</h2>
{% assign posts = site.posts | where:"lang", page.lang %}
{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}

{% capture written_label %}'None'{% endcapture %}

{% for collection in site.collections %}
{% unless collection.output == false or collection.label == "posts" %}
  {% capture label %}{{ collection.label }}{% endcapture %}
  {% if label != written_label %}
  <h2>{{ site.data.ui-text[page.lang][label] }}</h2>
  {% capture written_label %}{{ label }}{% endcapture %}
  {% endif %}
{% endunless %}
{% assign docs = collection.docs | where:"lang", page.lang %}
{% for post in docs %}
  {% unless collection.output == false or collection.label == "posts" %}
  {% include archive-single.html %}
  {% endunless %}
{% endfor %}
{% endfor %}
