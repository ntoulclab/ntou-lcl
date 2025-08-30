---
title: Alumnis
---
# {% include icon.html icon="fa-solid fa-users" %}Alumnis
## 2024年畢業生
{% assign images = "images/hong.jpg|images/cheng.jpg" | split: "|" %}
{% assign names = "洪于策 Yu-Tse Hung|陳建謀 Jian-Mou Chen" | split: "|" %}
{% assign emails = "11053035@mail.ntou.edu.tw|11153012@mail.ntou.edu.tw" | split: "|" %}
{% include image-grid.html %}
## 2025年畢業生
{% assign images = "images/apple.jpg|images/su.jpg|images/lee.jpg|images/young.jpg|images/yh.jpg|images/chae.jpg|images/mao2.jpg" | split: "|" %}
{% assign names = "曾聖雅 Sheng-Ya Tseng|蘇冠楷 Guan-Kai Su|李政霖 Cheng-Lin Li|楊啓宏 Qi-Hong Yang|江育翰 Yu-Han Jiang|蔡宗佑 Zong-You Cai|胡惇貿 DUN-MAO HU" | split: "|" %}
{% assign emails = "11153087@mail.ntou.edu.tw|michael0922851688@gmail.com|11253010@mail.ntou.edu.tw|11253037@mail.ntou.edu.tw|11253039@mail.ntou.edu.tw|11253107@mail.ntou.edu.tw|mouei0906@gmail.com" | split: "|" %}
{% include image-grid.html %}

<!-- {% capture content %}


{% endcapture %}

{% include grid.html style="square" content=content %} -->
