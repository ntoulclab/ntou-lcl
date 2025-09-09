---
title: Member
nav:
  order: 3
  tooltip: About our team
---
{% include section.html %}
# {% include icon.html icon="fa-solid fa-users" %}Principal Investigator

{% capture text %}
助理教授
(Assistant Professor)  

國立臺灣大學電機工程學系博士
(Ph.D. in Electrical Engineering, National Taiwan University)  

專長:  控制工程、非線性系統、強化學習、多代理人系統 
(Expertise: Control Engineering, Nonlinear Systems, Reinforcement Learning, Multi-Agent Systems) 

Office:EE2 R620

Phone:(02)24622192 ext 6205  

Email: mingli@mail.ntou.edu.tw

{% endcapture %}

{%
  include professor.html
  image="images/mingli.jpg"
  title="江明理 Ming-Li Chiang, Ph.D."
  text=text
%}


<!-- section break -->
# {% include icon.html icon="fa-solid fa-users" %}​Master Students

## 碩二
{% assign images = "images/bofan.jpg|images/TINTU.jpg|images/li2.jpg|images/lin.jpg|images/huang.jpg|images/tin.jpg|images/anyat.jpg|images/shung.jpg" | split: "|" %}

{% assign names = "陳柏帆 BO-FAN CHEN|丁昱鈞 YU-JUN DING|李登峰 DENG-FENG LI|林易廷 YI-TING LIN|黃冠霖 GUAN-LIN HUANG|戴廷宇 TING-YU DAI|胡安亞 ANAYAT|張皓翔 HAO-XIANG ZHANG" | split: "|" %}

{% assign emails = "401005brian@gmail.com|11353003@email.ntou.edu.tw|A24669855@gmail.com|Zed10487@gmail.com|11353007@mail.ntou.edu.tw|somewhitedie@gmail.com|@mail.ntou.edu.tw|11353117@email.ntou.edu.tw" | split: "|" %}
{% include image-grid.html %}

## 碩一
{% assign images = "images/kuanyu.jpg|images/cheyu.JPG|images/kuancheng.jpg|images/yuju.jpg" | split: "|" %}

{% assign names = "王寬裕 KUAN-YU WANG|周哲宇 CHE-YU CHOU|鄒冠程 KUAN-CHENG TSOU|陳郁儒 YU-JU CHEN" | split: "|" %}

{% assign emails = "vic2667@gmail.com|johnny890222@gmail.com|zouguancheng@gmail.com|11353093@mail.ntou.edu.tw" | split: "|" %}
{% include image-grid.html %}
<!-- section break -->
# {% include icon.html icon="fa-solid fa-users" %}​In-service Master Students
{% assign images = "images/kwen.jpg|images/CY.jpg|images/JASON.jpg" | split: "|" %}

{% assign names = "鍾文幀 WEN-ZHENG ZHONG|陳羿宏 YI-HONG CHEN|李至偉 ZHI-WEI LI" | split: "|" %}

{% assign emails = "kaitlyshawnrt@gmail.com|junesixteen25@gmail.com|j0988251682@gmail.com" | split: "|" %}
{% include image-grid.html %}
<!-- section break -->
# {% include icon.html icon="fa-solid fa-users" %}Undergraduate Students

{% assign images = "images/yea.jpg|images/hongp.jpg|images/cheao.jpg|images/yung.jpg|images/chang.jpg|images/yongyu.jpg|images/wen.jpg" | split: "|" %}

{% assign names = "葉沛妤 PEI-YU YE|洪珮珈 PEI-JIA HONG|邱意婷 YI-TING QIU|袁子婷 ZI-TING YUAN|張士成 SHI-CHENG ZHANG|莊詠瑜 YONG-YU ZHUANG|溫翔宇SIANG-YU WEN" | split: "|" %}

{% assign emails = "@mail.ntou.edu.tw|@mail.ntou.edu.tw|@mail.ntou.edu.tw|@mail.ntou.edu.tw|@mail.ntou.edu.tw|@mail.ntou.edu.tw|@mail.ntou.edu.tw" | split: "|" %}
{% include image-grid.html %}
<!-- section break -->
# {% include icon.html icon="fa-solid fa-users" %}[Alumnis](/ntou-lcl/members/Alumni)

<!-- {% capture content %}


{% endcapture %}

{% include grid.html style="square" content=content %} -->
