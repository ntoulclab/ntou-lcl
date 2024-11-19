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

# {% include icon.html icon="fa-solid fa-microscope" %}Competition

<ul>
{% for subcategory in page.subcategories %}
  <li>
    <a href="{{ subcategory.url }}">{{ subcategory.title }}</a>
  </li>
{% endfor %}
</ul>

{% endcapture %}
{%
  include feature.html
  image="images/Multi-UAV.png"
  title="<a href="/ntou-lcl/competition/Multi_UAV">基於多無人機編隊與影像辨識之遇難者搜救與定位系統</a>"
  flip=true
  text=""
%}

{% endcapture %}
{%
  include feature.html
  image="images/Image-Based.png"
  title="<a href="/ntou-lcl/competition/Image_Based">基於影像辨識之後車防撞警示邊緣計算輔助系統</a>"
  flip=true
  text=""
%}
