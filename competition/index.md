---
title: Competition
nav:
  order: 7
  tooltip: Competition Areas
subcategories:
  - title: 基於多無人機編隊與影像辨識之遇難者搜救與定位系統
    url: "/ntou-lcl/competition/Multi_UAV"
  - title: 基於影像辨識之後車防撞警示邊緣計算輔助系統
    url: "/ntou-lcl/competition/Image_Based"
---

<nav class="navbar">
  <ul class="nav-list">
    <li class="nav-item dropdown">
      <a href="/ntou-lcl/competition/">Competition</a>
      <ul class="dropdown-menu">
        {% for subcategory in page.subcategories %}
            <li><a href="{{ subcategory.url }}">{{ subcategory.title }}</a></li>
        {% endfor %}
      </ul>
    </li>
  </ul>
</nav>

# Research Areas

Explore our research areas:

<ul>
{% for subcategory in page.subcategories %}
  <li>
    <a href="{{ subcategory.url }}">{{ subcategory.title }}</a>
  </li>
{% endfor %}
</ul>

# {% include icon.html icon="fa-solid fa-microscope" %}Research

## Control of Multi-Agent System 多代理人系統控制

{% capture text %}
Cooperative Control of MAS  

Formation Control of UAVs  

Multi-UAV System Design and Applications  

Nonlinear and Adaptive Control Theory

{% endcapture %}
{%
  include feature.html
  image="images/UAV.jpg"
  title=""
  flip=true
  text=text
%}


## Development of Unmanned Vehicle System 無人載具系統發展

{% capture text %}
Robot Operating System (ROS)  

Automated Driving System (ADS)  

Autonomous Moving Robot (AMR)

{% endcapture %}
{%
  include feature.html
  image="images/AD.jpg"
  title=""
  flip=true
  text=text
%}

## Rinforcement Learning Control and Its Applications 強化學習控制與應用

{% capture text %}
Reinforcement Learning Control  

Actor-Critic Neural Network  

Deep Reinforcement Learning Control and Applications

{% endcapture %}
{%
  include feature.html
  image="images/RL.jpg"
  title=""
  flip=true
  text=text
%}
