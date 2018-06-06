---
layout: topic
title: "PyTorch Taipei 2018春季 (讀書會資訊與連結整理)"
date: 2018-06-06
modified: 2018-06-06
tags: #[PyTorchTP, DL]
image:
  feature: pytorch-header.jpg
fbcomments: yes
description: "PyTorch Taiwan是Marcel Wang先生為促進台灣深度學習發展，在網路上號召成立的深度學習讀書會，目前有台北、台中和新竹三分會 | PyTorch Taipei"
TopicShare: true
---

{% include toc.html %}

## 1. PyTorch Taipei 緣起

[PyTorch Taiwan](https://www.facebook.com/groups/2027602154187130/){:target="_blank"}是[Marcel Wang](https://www.linkedin.com/in/marcel-wang-3a988b7a/){:target="_blank"}先生為促進台灣深度學習發展，在網路上號召成立的深度學習讀書會，
<br>目前有[台北](http://hemingwang.blogspot.tw/2018/01/pytorchpytorch-taipei_20.html){:target="_blank"}、[新竹](http://hemingwang.blogspot.tw/2018/01/pytorchpytorch-hsinchu.html){:target="_blank"}和[台中](http://hemingwang.blogspot.tw/2018/04/pytorchpytorch-taichung_26.html){:target="_blank"}三個子分會。

<img src="../../images/pytp1.jpg">

2018.03.08 第一次讀書會(PC: [Eric Yang](https://www.facebook.com/profile.php?id=1561001417){:target="_blank"})

## 2. 講者徵求

讀書會2018年秋季以後之舉辦時間地點仍洽談中(預計仍是每周四晚上，地點為台大資工系德田館)，讀書會進行方式待徵完講者後也會再討論。

若有興趣當講者，請先至[此文](https://www.facebook.com/groups/2027602154187130/permalink/2060273964253282/){:target="_blank"}留言，會有人將您加進Facebook的報告者聊天視窗，要記得說明一下想報告下面進度表中的哪個題目。

<br><br>

## 3. 進度表

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

|      | CNN               |                                                                                                                                                                                                    |      | Pre-R-CNN |                                                                                              |      | R-CNN        |                                   
| ----:|:-----------------:| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----:|:---------:| -------------------------------------------------------------------------------------------- | ----:|:------------:| -------------------------------------------------------------------------------------------
| 3/08 | LeNet             | [![][p]][1]{:target="_blank"} [![][m]][20]{:target="_blank"} [![][v]][100]{:target="_blank"}<br> [![][c]][c1]{:target="_blank"}                                                                    | 4/26 | PreVGG    | [![][p]][8]{:target="_blank"}  [![][m]][29]{:target="_blank"} [      ][93]{:target="_blank"} | 6/14 | R-CNN        | [![][p]][14]{:target="_blank"} [      ][35]{:target="_blank"} [      ][87]{:target="_blank"}
| 3/08 | AlexNet           | [![][p]][2]{:target="_blank"} [![][m]][21]{:target="_blank"} [![][v]][99]{:target="_blank"} <br> [![][t]][t1]{:target="_blank"} [![][vt]][vt1]{:target="_blank"}                                   | 5/03 | SVM       | [![][p]][9]{:target="_blank"}  [![][m]][30]{:target="_blank"} [![][v]][92]{:target="_blank"} | 6/21 | SPPNet       | [![][p]][15]{:target="_blank"} [      ][36]{:target="_blank"} [      ][86]{:target="_blank"}
| 3/15 | ZFNet             | [![][p]][3]{:target="_blank"} [![][m]][22]{:target="_blank"} [![][v]][98]{:target="_blank"}                                                                                                        | 5/10 | 暫停一次  |                                                                                              | 6/28 | Fast R-CNN   | [![][p]][16]{:target="_blank"} [      ][37]{:target="_blank"} [      ][85]{:target="_blank"}
| 3/22 | NIN               | [![][p]][4]{:target="_blank"} [![][m]][23]{:target="_blank"} [![][v]][97]{:target="_blank"}                                                                                                        | 5/17 | SMO       | [![][p]][10]{:target="_blank"} [![][m]][31]{:target="_blank"} [![][v]][91]{:target="_blank"} | 7/05 | Faster R-CNN | [![][p]][17]{:target="_blank"} [      ][38]{:target="_blank"} [      ][84]{:target="_blank"}
| 3/29 | GoogLeNet         | [![][p]][5]{:target="_blank"} [![][m]][26]{:target="_blank"} [![][v]][96]{:target="_blank"}                                                                                                        | 5/24 | DPM       | [![][p]][11]{:target="_blank"} [      ][32]{:target="_blank"} [![][v]][90]{:target="_blank"} [![][c]][DPMd]{:target="_blank"} | 7/12 | YOLO v1      | [![][p]][18]{:target="_blank"} [      ][39]{:target="_blank"} [      ][83]{:target="_blank"} [![][c]][Yv1]{:target="_blank"}
| 4/12 | VGGNet<br>ResNet  | [![][p]][6]{:target="_blank"} [![][m]][27]{:target="_blank"} [![][v]][95]{:target="_blank"}<br> [![][p]][6.5]{:target="_blank"} [![][t]][tres]{:target="_blank"} [![][vt]][vres]{:target="_blank"} | 5/31 | SS        | [![][p]][12]{:target="_blank"} [      ][33]{:target="_blank"} [      ][89]{:target="_blank"} | 7/19 | SSD          | [![][p]][19]{:target="_blank"} [      ][40]{:target="_blank"} [      ][82]{:target="_blank"} [![][c]][cssd]{:target="_blank"}
| 4/19 | SqueezeNet        | [![][p]][7]{:target="_blank"} [![][m]][28]{:target="_blank"} [![][v]][94]{:target="_blank"}<br> [![][c]][sqc]{:target="_blank"}                                                                    | 6/07 | FCN       | [![][p]][13]{:target="_blank"} [      ][34]{:target="_blank"} [      ][88]{:target="_blank"} | 另訂 | YOLO v2&v3   | v2[ ![][p]][24]{:target="_blank"} [![][c]][Yv2]{:target="_blank"}<br> v3[ ![][p]][25]{:target="_blank"}  [![][c]][Yv3]{:target="_blank"}

[p]: ../../images/icons/paper.png
[c]: ../../images/icons/coding.png
[v]: ../../images/icons/video.png
[t]: ../../images/icons/pytorch.png
[vt]: ../../images/icons/video_t.png
[m]: ../../images/icons/mt.png

<!-- LeNet -->
[1]: http://yann.lecun.com/exdb/publis/pdf/lecun-98.pdf
[20]:https://hackmd.io/p/BkxYFCnOM#/
[100]: https://youtu.be/5F7SnpjTas8?t=5m30s
[c1]: http://yann.lecun.com/exdb/lenet/index.html

<!-- AlexNet -->
[2]: http://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf
[21]:https://medium.com/@WhoYoung99/alexnet-架構概述-988113c06b4b
[99]: https://youtu.be/5F7SnpjTas8?t=32m42s
[vt1]: https://youtu.be/e8m46iiBuzw?t=26m7s
[t1]: https://github.com/pecu/PyTorch_CSX/tree/master/02_AlexNet

<!-- ZFNet -->
[3]: https://arxiv.org/pdf/1311.2901.pdf
[22]:https://www.dropbox.com/s/rrgc205ffedims8/ZFNet_shape.pdf
[98]: https://www.youtube.com/watch?v=e8m46iiBuzw

<!-- NIN -->
[4]: https://arxiv.org/pdf/1312.4400.pdf
[23]:https://www.slideshare.net/gilbert6555tw/nin-20180319-91529205
[97]: https://www.youtube.com/watch?v=BkvywRsPPuA

<!-- GoogLeNet -->
[5]: http://openaccess.thecvf.com/content_cvpr_2015/papers/Szegedy_Going_Deeper_With_2015_CVPR_paper.pdf
[26]: https://drive.google.com/file/d/1QPOgFV5WXUaNaq5SG9UPzp_qMpTt8-8g/view?usp=sharing
[96]: https://www.youtube.com/watch?v=XHTwKN7BYhc

<!-- VGGNet -->
[6]: https://arxiv.org/pdf/1409.1556/
[27]: https://medium.com/@danjtchen/vgg-%E6%B7%B1%E5%BA%A6%E5%AD%B8%E7%BF%92-%E5%8E%9F%E7%90%86-d31d0aa13d88
[95]: https://www.youtube.com/watch?v=XmLeY953zaY

<!-- ResNet -->
[6.5]: https://arxiv.org/pdf/1512.03385
[vres]: https://www.youtube.com/watch?v=yaJcF1KLVX0
[tres]: https://github.com/pecu/PyTorch_CSX/tree/master/05_Deep_Residual_Network

<!-- SqueezeNet -->
[7]: https://arxiv.org/pdf/1602.07360.pdf
[28]: https://docs.google.com/presentation/d/168-z3psekR4FnJWVV6IMaEyBR9RMvWjHtD9BPHvzKtI/edit#slide=id.g384c0c5446_0_334
[94]: https://www.youtube.com/watch?v=LI2WDTAslbY
[sqc]: https://github.com/DeepScale/SqueezeNet

<!-- PreVGG -->
[8]: http://people.idsia.ch/~juergen/ijcai2011.pdf
[29]: https://medium.com/@ChrisChou0426/pytorch-taipei-paper-flexible-high-performance-convolutional-neural-networks-for-image-4153f9495113
[93]: https://youtu.be/

<!-- SVM -->
[9]:  http://w.svms.org/training/BOGV92.pdf
[30]: https://rickychang-blog.herokuapp.com/support-vector-machine/
[92]: https://www.youtube.com/watch?v=hN6d5cwJYI0

<!-- SMO -->
[10]: https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/tr-98-14.pdf
[91]: https://www.youtube.com/watch?v=UG0AEcfBe1A
[31]: https://drive.google.com/open?id=1toBxIRGRp364k_uXRgCy9Zcv-J4YmJZV

<!-- DPM -->
[11]: https://cs.brown.edu/~pff/papers/lsvm-pami.pdf
[90]: https://www.youtube.com/watch?v=uzTHFNpQ_9E
[DPMd]: http://www.rossgirshick.info/latent/
[32]: ...

<!-- SS -->
[12]: https://ivi.fnwi.uva.nl/isis/publications/2013/UijlingsIJCV2013/UijlingsIJCV2013.pdf
[89]: https://youtu.be/
[33]: ....

<!-- FCN -->
[13]: https://www.cv-foundation.org/openaccess/content_cvpr_2015/app/2B_011.pdf
[88]: https://youtu.be/
[34]: ....

<!-- R-CNN -->
[14]: https://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Girshick_Rich_Feature_Hierarchies_2014_CVPR_paper.pdf?spm=5176.100239.blogcont55892.8.pm8zm1&file=Girshick_Rich_Feature_Hierarchies_2014_CVPR_paper.pdf
[87]: https://youtu.be/
[35]: ....

<!-- SPPNet -->
[15]: https://arxiv.org/pdf/1406.4729.pdf
[86]: https://youtu.be/
[36]: ....

<!-- Fast -->
[16]: http://openaccess.thecvf.com/content_iccv_2015/papers/Girshick_Fast_R-CNN_ICCV_2015_paper.pdf
[85]: https://youtu.be/
[37]: ....

<!-- Faster -->
[17]: http://papers.nips.cc/paper/5638-faster-r-cnn-towards-real-time-object-detection-with-region-proposal-networks.pdf
[84]: https://youtu.be/
[38]: ....

<!-- SSD -->
[19]: https://arxiv.org/pdf/1512.02325.pdf
[cssd]: https://github.com/weiliu89/caffe/tree/ssd
[82]: https://youtu.be/
[40]: ....

<!-- YOLO -->
<!-- v1 -->
[39]: ....
[Yv1]: https://pjreddie.com/darknet/yolov1/
[83]: https://youtu.be/
[18]: https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Redmon_You_Only_Look_CVPR_2016_paper.pdf
<!-- v23 -->
[Yv2]: https://pjreddie.com/darknet/yolov2/
[Yv3]: https://pjreddie.com/darknet/yolo/
[24]: https://arxiv.org/pdf/1612.08242
[25]: https://pjreddie.com/media/files/papers/YOLOv3.pdf
[81]: https://youtu.be/
[80]: https://youtu.be/
