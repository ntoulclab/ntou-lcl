---
title: 基於多無人機編隊與影像辨識之遇難者搜救與定位系統
parent: UAV_System_Design
---

## 基於多無人機編隊與影像辨識之遇難者搜救與定位系統<br>Multi-UAV Formation-Based Search and Rescue System for Victim Localization Using Image Recognition
<div class="container">
  <div class="text">
    <p>本作品旨在研發一套多無人機的編隊搜救系統，專門用於搜救山難及海上失聯船隻。結合路徑規劃、影像辨識、無人機編隊控制及GPS與RTK精準定位技術，大幅提升搜救效率與可靠性。系統的主要創新點在於靈活的編隊控制和協同操作，使無人機可根據任務需求動態調整隊形，最大化攝影範圍，確保對搜尋區域的無縫覆蓋。系統採用了YOLOv5模型，可快速識別遇難人員或船隻，當無人機拍攝到搜救目標時，系統即時判斷目標相對位置，並通過距離估計與座標轉換計算出精確經緯度，立刻回傳給搜救人員迅速展開行動。</p>
  </div>
  <div class="image">
    <img src="../../images/Multi-UAV.png" alt="搜救系統概要">
  </div>
</div>

<iframe width="1024" height="576" src="https://www.youtube.com/embed/G6fGhG5sQbs" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
