---
title: Alumnis
---
# {% include icon.html icon="fa-solid fa-users" %}Alumnis
## 2024年畢業生
{% assign images = "images/hong.jpg|images/cheng.jpg" | split: "|" %}

{% assign names = "洪于策 Yu-Tse Hung|陳建謀 Jian-Mou Chen" | split: "|" %}

{% assign emails = "11053035@mail.ntou.edu.tw|11153012@mail.ntou.edu.tw" | split: "|" %}
{% include image-grid.html %}

<!-- {% capture content %}


{% endcapture %}

{% include grid.html style="square" content=content %} -->
