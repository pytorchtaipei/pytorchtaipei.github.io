---
layout: topic
title: "PyTorch Taipei 2018秋季: 講者徵求中!!"
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

若有興趣當講者，請先至[此文](https://www.facebook.com/groups/2027602154187130/permalink/2060273964253282/){:target="_blank"}留言，會有人將您加進Facebook的報告者聊天視窗，請記得說明一下想報告的主題(特定論文或是NLP/數學)。若有興趣的主題在下表中已經列有講者也沒關係，我們希望每個主題都能有多人一起討論，一個主題也可能需要多位講者(每周一位)，列在下表的即為該主題的負責人。

下列的進度表僅初步規劃，為上半場的論文討論主題，每個主題可能是1~3周不等的報告份量，目前主要是接續春季YOLO和Inception的改進版本、以及optimization, normalization, regularization技巧。下半場會是NLP和深度學習相關的數學，目前仍在規劃中，有興趣的講者可以先報名，待日程表確定後再讓大家選擇主題。

有甚麼想法歡迎在[Facebook社團](https://www.facebook.com/groups/2027602154187130/){:target="_blank"}一起討論。

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

| 主題                                | 講者                | 連結&備註
|:-----------------------------------:|:--------------------| ------
| YOLO v2<br/>YOLO v3                 | 林家豪<br/>郭瑞申   | v2 [![][p]][Yv2p]{:target="_blank"} [![][c]][Yv2]{:target="_blank"} <br/>v3 [![][p]][Yv3p]{:target="_blank"} [![][c]][Yv3]{:target="_blank"}
| MobileNet                           | 郭宗賢              |
| Gradient Descent <br/>& Momentum    | 蔡皓璿              | BGD, SGD, Mini-batch GD, NAG
| Adaptive Methods                    | 王威翔              | AdaGrad, AdaDelta, RMSprop
| Adaptive Methods <br/>with Momentum | Rose Teng           | Adam, AdaMax
| Improvements of Adam                | Eric Lin            | NAdam, AMSGrad
| Inception v2<br/>Inception v3, v4   | Eric Lin<br/>楊哲寧 | v2為Batch Normalization<br/>.
| Layer Normalization                 | 缺                  | 楊明翰
| Group Normalization                 | 缺                  |  
| Regularization                      | 缺                  | [weight decay](http://hemingwang.blogspot.com/2017/06/aiweight-decay.html){:target="_blank"}, dropout, dropconnect, L1, L2
| RNN                                 | 林振雄              |    

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
