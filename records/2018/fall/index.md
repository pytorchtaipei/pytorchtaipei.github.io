---
layout: topic
title: "PyTorch Taipei 2018秋季 (讀書會資訊與連結整理)"
date: 2018-06-06
modified: 2018-06-06
tags: #[PyTorchTP, DL]
image:
  feature: pytorch-header.jpg
fbcomments: yes
description: "PyTorch Taiwan是Marcel Wang先生為促進台灣深度學習發展，在網路上號召成立的深度學習讀書會，目前有台北、台中和新竹三個子分會 | PyTorch Taipei"
TopicShare: true
---

{% include toc.html %}

## 1. PyTorch Taipei 緣起

[PyTorch Taiwan](https://www.facebook.com/groups/2027602154187130/){:target="_blank"}是[Marcel Wang](https://www.linkedin.com/in/marcel-wang-3a988b7a/){:target="_blank"}先生為促進台灣深度學習發展，在網路上號召成立的深度學習讀書會，
目前有[台北](http://hemingwang.blogspot.tw/2018/01/pytorchpytorch-taipei_20.html){:target="_blank"}、[新竹](http://hemingwang.blogspot.tw/2018/01/pytorchpytorch-hsinchu.html){:target="_blank"}和[台中](http://hemingwang.blogspot.tw/2018/04/pytorchpytorch-taichung_26.html){:target="_blank"}三分會。

<img src="../../../images/pytp1.jpg">

2018.03.08 第一次讀書會(PC: [Eric Yang](https://www.facebook.com/profile.php?id=1561001417){:target="_blank"})

## 2. 講者徵求

讀書會2018年秋季之舉辦時間和地點仍在洽談中(預計仍是每周四晚上19:00~21:00，地點改為台大資工系德田館)，讀書會進行方式待徵完講者後也會再討論。

若有興趣當講者，請先至[此文](https://www.facebook.com/groups/2027602154187130/permalink/2060273964253282/){:target="_blank"}留言，會有人將您加進Facebook的報告者聊天視窗，
可以的話記得說明一下想報告下面進度表中的哪個題目。若有興趣的主題在下表中已經列有講者也沒關係，我們希望每個主題都能有多人一起討論，列在下表的即為該次報告的負責人。

## 3. 進度表

此進度表僅初步規劃，之後還有可能會新增主題，但主要是接續春季YOLO和Inception的改進版本、以及機器學習的optimization, normalization, regularization，大家有甚麼想法也歡迎在[Facebook社團](https://www.facebook.com/groups/2027602154187130/){:target="_blank"}一起討論。

<!--
<link rel="stylesheet" href="./custom.css">
<div class="w3-row">
  <div class="w3-quarter w3-container">
    <p><img src="../../images/icons/gd.png" alt="" /> <a href="https://drive.google.com/open?id=12AYDi8JCsqYVXJH7jbexuu3LHtqtudiz" target="_blank">全部論文下載</a><br>
    <img src="../../images/icons/gds.png" alt="" /> <a href="https://docs.google.com/spreadsheets/d/1qYJ5rOL7gotjbcXTVPDvclyZptZ-cRpYcDbdWk3PMt4/edit?usp=sharing" target="_blank">每周講者列表</a><br>
    <img src="../../images/icons/github.png" alt="" /> <a href="https://github.com/pecu/PyTorch_CSX" target="_blank">實作進度表</a><br><img src="../../images/icons/youtube.png" alt="" /> <a href="https://www.youtube.com/channel/UCk_f2g9Dkc4WaqrqpzxywJw" target="_blank">PyTorchTP</a></p>
  </div>
  <div class="w3-quarter w3-container">
    <p><img src="../../images/icons/paper.png" alt="" />: 論文PDF<br>
    <img src="../../images/icons/mt.png" alt="" />: 講者之講解材料<br>
    <img src="../../images/icons/video.png" alt="" />: 論文講解影片連結</p>
  </div>
  <div class="w3-quarter w3-container">
    <p><img src="../../images/icons/coding.png" alt="" />: 官方程式/Demo<br>
    <img src="../../images/icons/pytorch.png" alt="" />: PyTorch範例程式<br>
    <img src="../../images/icons/video_t.png" alt="" />: PyTorch講解影片</p>
  </div>
</div>
-->



| 主題                          | 講者              | 連結&備註 | 主題                          | 講者              | 連結&備註
|:-----------------------------:|:-----------------:| ------|:-----------------------------:|:-----------------:| ------
| YOLO v2&v3                    | 林家豪<br/>郭瑞申 | v2 [![][p]][Yv2p]{:target="_blank"} [![][p]][Yv2]{:target="_blank"} <br/>v3 [![][p]][Yv3p]{:target="_blank"} [![][p]][Yv3]{:target="_blank"} | Batch Normalization           | Eric Lin          |
| Inception v2&v3               | 楊哲寧<br/>       | 希望至少再一位負責人<br/>(論文份量可能需要分兩周報告) | Layer Normalization           | 缺                |
| Gradient Descent <br/>& Momentum | 蔡皓璿            | BGD, SGD, Mini-batch GD, NAG | Group Normalization           | 缺                |
| Adaptive Methods              | 王威翔            | AdaGrad, AdaDelta, RMSprop | weight decay                  | 缺                | [參考文章](http://hemingwang.blogspot.com/2017/06/aiweight-decay.html){:target="_blank"}
| Adaptive Methods <br/>with Momentum | Rose Teng         | Adam, AdaMax | dropout                       | 缺                | 
| Improvements of Adam          | Eric Lin          | NAdam, AMSGrad | RNN |林振雄 |

[p]: ../../../images/icons/paper.png
[c]: ../../../images/icons/coding.png
[v]: ../../../images/icons/video.png
[t]: ../../../images/icons/pytorch.png
[vt]: ../../../images/icons/video_t.png
[m]: ../../../images/icons/mt.png

<!-- YOLO v23 -->
[Yv2]: https://pjreddie.com/darknet/yolov2/
[Yv3]: https://pjreddie.com/darknet/yolo/
[Yv2p]: https://arxiv.org/pdf/1612.08242
[Yv3p]: https://pjreddie.com/media/files/papers/YOLOv3.pdf


