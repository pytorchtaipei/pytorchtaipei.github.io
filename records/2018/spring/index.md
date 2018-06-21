---
layout: topic
title: "PyTorch Taipei 2018春季: 讀書會資訊與連結整理"
date: 2018-02-28
modified: 2018-04-17
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

<img src="../../../images/pytp1.jpg">

2018.03.08 第一次讀書會(PC: [Eric Yang](https://www.facebook.com/profile.php?id=1561001417){:target="_blank"})

## 2. 讀書會資訊
時間: 每週四19:00~21:00

內容: 分兩部份進行，可隨時於[線上討論區](https://discord.gg/jMCVCbJ){:target="_blank"}發問。

1. 經典論文導讀
 - 預計進行18周
 - 參加者建議已具備ML/DL/CNN[](../basic-CNN-FP){:target="_blank"}基礎知識

2. PyTorch實作
 - 由台大CS+X計畫負責人[Pecu老師](https://www.facebook.com/pecu.tsai){:target="_blank"}及其團隊負責帶領
 - [公佈欄&進度表](https://github.com/pecu/PyTorch_CSX){:target="_blank"}

地點: 台灣大學普通教學館305教室 (6/28前)

停車資訊:

   * [台大校內停車地點](http://general.ga.ntu.edu.tw/uploads/archive_file_multiple/file/56d1ee4f48b8a10b9200024b/%E6%A0%A1%E7%B8%BD%E5%8D%80%E6%B1%BD%E6%A9%9F%E8%BB%8A%E5%81%9C%E8%BB%8A%E5%A0%B4%E5%8D%80%E4%BD%8D%E5%9C%96-103-09.pdf){:target="_blank"}及[收費規則](http://general.ga.ntu.edu.tw/zh_tw/qa/校園臨時停車收費費率-22859878){:target="_blank"}
   * 校友若持[校友證]( http://www.alumni.ntu.edu.tw/card_benefits.html ){:target="_blank"}則能以優惠價格停車

<iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d5187.408040986593!2d121.5353681110393!3d25.018345685786382!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3442a989deb9207f%3A0x8de176bf66b58b1d!2z5Y-w54Gj5aSn5a245pmu6YCa5pWZ5a246aSo!5e0!3m2!1szh-TW!2sus!4v1526145553086" width="600" height="380" frameborder="0" style="border:0" allowfullscreen></iframe>

<br><br>

## 3. 進度表與連結整理

**6/7以後場次CS+X團隊無法支援錄影器材，不會有講解影片**

<link rel="stylesheet" href="./custom.css">
<!-- <link rel="stylesheet" href="https://www.w3schools.com/lib/w3-theme-black.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.3.0/css/font-awesome.min.css"> -->
<div class="w3-row">
  <div class="w3-quarter w3-container">
    <p><img src="../../../images/icons/gd.png" alt="" /> <a href="https://drive.google.com/open?id=12AYDi8JCsqYVXJH7jbexuu3LHtqtudiz" target="_blank">全部論文下載</a><br>
    <img src="../../../images/icons/gds.png" alt="" /> <a href="https://docs.google.com/spreadsheets/d/1qYJ5rOL7gotjbcXTVPDvclyZptZ-cRpYcDbdWk3PMt4/edit?usp=sharing" target="_blank">每周講者列表</a><br>
    <img src="../../../images/icons/github.png" alt="" /> <a href="https://github.com/pecu/PyTorch_CSX" target="_blank">實作進度表</a><br><img src="../../../images/icons/youtube.png" alt="" /> <a href="https://www.youtube.com/channel/UCk_f2g9Dkc4WaqrqpzxywJw" target="_blank">PyTorchTP</a></p>
  </div>
  <div class="w3-quarter w3-container">
    <p><img src="../../../images/icons/paper.png" alt="" />: 論文PDF<br>
    <img src="../../../images/icons/mt.png" alt="" />: 講者之講解材料<br>
    <img src="../../../images/icons/video.png" alt="" />: 論文講解影片連結</p>
  </div>
  <div class="w3-quarter w3-container">
    <p><img src="../../../images/icons/coding.png" alt="" />: 官方程式/Demo<br>
    <img src="../../../images/icons/pytorch.png" alt="" />: PyTorch範例程式<br>
    <img src="../../../images/icons/video_t.png" alt="" />: PyTorch講解影片</p>
  </div>
</div>


|      | CNN               |                                                                                                                                                                                                    |      | Pre-R-CNN |                                                                                              |      | R-CNN        |                                   
| ----:|:-----------------:| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----:|:---------:| -------------------------------------------------------------------------------------------- | ----:|:------------:| -------------------------------------------------------------------------------------------
| 3/08 | LeNet             | [![][p]][1]{:target="_blank"} [![][m]][20]{:target="_blank"} [![][v]][100]{:target="_blank"}<br> [![][c]][c1]{:target="_blank"}                                                                    | 4/26 | PreVGG    | [![][p]][8]{:target="_blank"}  [![][m]][29]{:target="_blank"} [      ][93]{:target="_blank"} | 6/14 | R-CNN        | [![][p]][14]{:target="_blank"} [      ][35]{:target="_blank"} 
| 3/08 | AlexNet           | [![][p]][2]{:target="_blank"} [![][m]][21]{:target="_blank"} [![][v]][99]{:target="_blank"} <br> [![][t]][t1]{:target="_blank"} [![][vt]][vt1]{:target="_blank"}                                   | 5/03 | SVM       | [![][p]][9]{:target="_blank"}  [![][m]][30]{:target="_blank"} [![][v]][92]{:target="_blank"} | 6/21 | SPPNet       | [![][p]][15]{:target="_blank"} [![][m]][36]{:target="_blank"} 
| 3/15 | ZFNet             | [![][p]][3]{:target="_blank"} [![][m]][22]{:target="_blank"} [![][v]][98]{:target="_blank"}                                                                                                        | 5/10 | 暫停一次  |                                                                                              | 6/28 | Fast R-CNN   | [![][p]][16]{:target="_blank"} [      ][37]{:target="_blank"} 
| 3/22 | NIN               | [![][p]][4]{:target="_blank"} [![][m]][23]{:target="_blank"} [![][v]][97]{:target="_blank"}                                                                                                        | 5/17 | SMO       | [![][p]][10]{:target="_blank"} [![][m]][31]{:target="_blank"} [![][v]][91]{:target="_blank"} | 7/05 | Faster R-CNN | [![][p]][17]{:target="_blank"} [![][m]][38]{:target="_blank"}
| 3/29 | GoogLeNet         | [![][p]][5]{:target="_blank"} [![][m]][26]{:target="_blank"} [![][v]][96]{:target="_blank"}                                                                                                        | 5/24 | DPM       | [![][p]][11]{:target="_blank"} [      ][32]{:target="_blank"} [![][v]][90]{:target="_blank"} [![][c]][DPMd]{:target="_blank"} | 7/12 | YOLO v1      | [![][p]][18]{:target="_blank"} [      ][39]{:target="_blank"} [![][c]][Yv1]{:target="_blank"}
| 4/12 | VGGNet<br>ResNet  | [![][p]][6]{:target="_blank"} [![][m]][27]{:target="_blank"} [![][v]][95]{:target="_blank"}<br> [![][p]][6.5]{:target="_blank"} [![][t]][tres]{:target="_blank"} [![][vt]][vres]{:target="_blank"} | 5/31 | SS        | [![][p]][12]{:target="_blank"} [      ][33]{:target="_blank"} [![][v]][89]{:target="_blank"} | 7/19 | SSD          | [![][p]][19]{:target="_blank"} [      ][40]{:target="_blank"} [![][c]][cssd]{:target="_blank"}
| 4/19 | SqueezeNet        | [![][p]][7]{:target="_blank"} [![][m]][28]{:target="_blank"} [![][v]][94]{:target="_blank"}<br> [![][c]][sqc]{:target="_blank"}                                                                    | 6/7  | 暫停一次  |                                                                                              | | | 

[p]: ../../../images/icons/paper.png
[c]: ../../../images/icons/coding.png
[v]: ../../../images/icons/video.png
[t]: ../../../images/icons/pytorch.png
[vt]: ../../../images/icons/video_t.png
[m]: ../../../images/icons/mt.png

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
[89]: https://www.youtube.com/watch?v=iGIFwPfhmZg
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
[36]: https://www.slideshare.net/whuang022ai/spatial-pyramid-pooling-in-deep-convolutional-networks-for-visual-recognition

<!-- Fast -->
[16]: http://openaccess.thecvf.com/content_iccv_2015/papers/Girshick_Fast_R-CNN_ICCV_2015_paper.pdf
[37]: ....

<!-- Faster -->
[17]: http://papers.nips.cc/paper/5638-faster-r-cnn-towards-real-time-object-detection-with-region-proposal-networks.pdf
[38]: https://python5566.wordpress.com/2018/06/19/deep-learning-notes-object-detection-models-faster-r-cnn-fcn/

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


|      |  PyTorch Basic  |                                                                      |      | NLP                          |                                                                      |      |  其他                  |                                                                    |
|-----:|:---------------:|----------------------------------------------------------------------|-----:|:----------------------------:|----------------------------------------------------------------------|-----:|:----------------------:|--------------------------------------------------------------------|
| 3/8  | PyTorch Basic   | [![][t]][PTBt]{:target="_blank"}                                     | 4/19 | Basic NLP                    | [![][t]][NLPt]{:target="_blank"} [![][vt]][NLPv]{:target="_blank"}   | 4/26 | Automated<br>Reasoning | [![][t]][AtRt]{:target="_blank"} [![][vt]][AtRv]{:target="_blank"}
| 3/15 | PyTorch Example | [![][t]][Pext]{:target="_blank"} [![][vt]][Pexv]{:target="_blank"}   | 4/26 | Seq2Seq                      | [![][t]][s2st]{:target="_blank"} [![][vt]][s2sv]{:target="_blank"}   | 5/3  | RL (DQN)               | [![][t]][DQNt]{:target="_blank"} [![][vt]][DQNv]{:target="_blank"}
| 3/29 | RNN             | [![][t]][RNNt]{:target="_blank"}[![][vt]][RNNv]{:target="_blank"}    | 5/17 | Seq2Seq with <br/> attention | [![][t]][s2sat]{:target="_blank"} [![][vt]][s2sav]{:target="_blank"} | 5/24 | Style Transfer         | [![][p]][STp]{:target="_blank"}  [![][m]][STt]{:target="_blank"} [![][vt]][STv]{:target="_blank"} <br/>[![][c]][STd]{:target="_blank"}
|      |                 |                                                                      |      |                              |                                                                      | 5/31 | Variational Auto-Encoder | [![][p]][VAEp]{:target="_blank"}  [![][t]][VAEt]{:target="_blank"} [![][vt]][VAEv]{:target="_blank"} <br/>[![][c]][VAEc]{:target="_blank"}

[PTBt]:https://github.com/pecu/PyTorch_CSX/tree/master/01_PyTorch_Basic
[Pext]:https://github.com/pecu/PyTorch_CSX/tree/master/03_Learning_PyTorch_with_Examples
[Pexv]:https://www.youtube.com/watch?v=BL-_mjIP_AY

[RNNt]: https://github.com/pecu/PyTorch_CSX/tree/master/04_RNN
[RNNv]:https://www.youtube.com/watch?v=YjgNjsdilNs
[NLPt]: https://github.com/pecu/PyTorch_CSX/tree/master/06_Natural_Language_Processing
[NLPv]:https://www.youtube.com/watch?v=OOL0OGUA9eU
[s2st]:https://github.com/d06521005/NLP_Competition/blob/master/basic_seq2seq.ipynb
[s2sv]:https://www.youtube.com/watch?v=5ieic6mvRpw

[s2sav]: https://www.youtube.com/watch?v=2f1jcq7H2u0
[s2sat]: https://github.com/pecu/PyTorch_CSX/tree/master/09_Attention_seq2seq

[AtRt]:https://github.com/pecu/PyTorch_CSX/tree/master/07_Automated_Reasoning
[AtRv]:https://www.youtube.com/watch?v=69kt1h_6SsM
[DQNt]:https://github.com/pecu/PyTorch_CSX/tree/master/08_DQN
[DQNv]:https://www.youtube.com/watch?v=8YGuGBLLKq0

[STp]: https://arxiv.org/abs/1508.06576
[STt]: ../../../articles/PyTorchTP-Style-Transfer/
[STv]: https://www.youtube.com/watch?v=G3gd5jo5nJA
[STd]: https://deepart.io

<!-- Variational Auto-Encoder -->
[VAEp]: https://arxiv.org/abs/1312.6114
[VAEv]: https://www.youtube.com/watch?v=dR9TXPl0Cgg
[VAEc]: https://github.com/pecu/PyTorch_CSX/tree/master/10_VAE
[VAEt]: https://ppt.cc/fbPNXx


