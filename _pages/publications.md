---
title: "Zhang Lab - Publications"
layout: gridlay
excerpt: "Zhang Lab -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

## Group highlights

**At the end of this page, you can find the [full list of publications and patents](#full-list-of-publications). All papers are also available on [arXiv](https://arxiv.org/search/?searchtype=author&query=Allan%2C+M+P).**

{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>


## Patents
<em>Milan P Allan, S Gröblacher, RA Norte, M Leeuwenhoek</em><br />Novel atomic force microscopy probes with phononic crystals<br /> PCT/NL20-20/050797 (2020)

<em>Milan P Allan</em><br /> Methods of manufacturing superconductor and phononic elements <br /> <a href="https://patents.google.com/patent/US10439125B2/en?inventor=Milan+ALLAN&oq=inventor:(Milan+ALLAN)">US10439125B2 (2016)</a>

## Full List of publications

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}

Zhaowei, Zhang*, Naizhou Wang*, Ning Cao, Aifeng Wang, Xiaoyuan Zhou, Kenji Watanabe, Takashi Taniguchi, Binghai Yan, and Wei-bo Gao. "Controlled large non-reciprocal charge transport in an intrinsic magnetic topological insulator MnBi2Te4." arXiv preprint arXiv:2203.09350 (2022). Nature Communications, 13.1 (2022): 6191. <br />

Zhaowei Zhang*, Jingzhi Shang*, Chongyun Jiang*, Abdullah Rasmita, Weibo Gao, Ting Yu. "Direct photoluminescence probing of ferromagnetism in monolayer two-dimensional CrBr3." Nano Letters (2019) 5: 3138-3142. <br />

Govindan Kutty Rajendran Nair*, Zhaowei Zhang*, Fuchen Hou*, Ali Abdelaziem*, Xiaodong Xu, Steve Wu Qing Yang, Nan Zhang, Weiqi Li, Chao Zhu, Yao Wu, Heng Weiling, Lixing Kang, Teddy Salim, Jiadong Zhou, Lin Ke, Junhao Lin, Xingji Li, Weibo Gao, Zheng Liu. "Phase-pure two-dimensional FexGeTe2 magnets with near-room-temperature TC". Nano Research 15.1 (2022): 457-464.<br />

[4] Naizhou Wang, Daniel Kaplan, Zhaowei Zhang, Tobias Holder, Ning Cao, Aifeng Wang, Xiaoyuan Zhou, Feifei Zhou, Zhengzhi Jiang, Chusheng Zhang, Shihao Ru, Hongbing Cai, Kenji Watanabe, Takashi Taniguchi, Binghai Yan, Weibo Gao. "Quantum metric-induced nonlinear transport in a topological antiferromagnet." Nature (2023): 1-2.
[5] Naizhou Wang, Jing-Yang You, Aifeng Wang, Xiaoyuan Zhou, Zhaowei Zhang, Shen Lai, Hung-Ju Tien, Tay-Rong Chang, Yuan-Ping Feng, Hsin Lin, Guoqing Chang, Wei-bo Gao, “Non-centrosymmetric topological phase probed by Nonlinear Hall effect”. National Science Review (2023): nwad103.
[6] Qinghai Tan, Abdullah Rasmita, Zhaowei Zhang, Hongbing Cai, Xiangbin Cai, Xuran Dai, Kenji Watanabe, Takashi Taniguchi, Allan H MacDonald, Weibo Gao, “Layer-dependent correlated phases in WSe2/MoS2 moiré superlattice”. Nature Materials (2023): 1-7.
[7] Hongbing Cai, Abdullah Rasmita, Qinghai Tan, Jia-Min Lai, Ruihua He, Disheng Chen, Naizhou Wang, Zhao Mu, Zumeng Huang, Zhaowei Zhang, John JH Eng, Yuanda Liu, Yongzhi She, Nan Pan, Xiaoping Wang, Xiaogang Liu, Jun Zhang, Weibo Gao, “Interlayer donor-acceptor pair excitons in MoSe2/WSe2 moiré heterobilayer”. Nature Communications 14, 5766 (2023).
[8] Shen Lai, Zhaowei Zhang, Naizhou Wang, Abdullah Rasmita, Ya Deng, Zheng Liu, Wei-bo Gao. “Dual-Gate All-Electrical Valleytronic Transistors”. Nano Letters 23.1(2023):192-197.
[9] Qinghai Tan, Abdullah Rasmita, Zhaowei Zhang, KS Novoselov, Wei-bo Gao.“ Signature of Cascade Transitions between Interlayer Excitons in a Moiré Superlattice”. Physical Review Letters 192.24(2022): 247401.
[10] Xiaodan Lyu, Qinghai Tan, Lishu Wu, Chusheng Zhang, Zhaowei Zhang, Zhao Mu, Jesús Zúñiga-Pérez, Hongbing Cai, Weibo Gao. “Strain Quantum Sensing with Spin Defects in Hexagonal Boron Nitride”. Nano Letters 22.16(2022) 6553-6559.
[11] Jiadong Zhou, Chao Zhu, Yao Zhou, Jichen Dong, Peiling Li, Zhaowei Zhang, Zhen Wang, Yung-Chang Lin, Jia Shi, Runwu Zhang, Yanzhen Zheng, Huimei Yu, Bijun Tang, Fucai Liu, Lin Wang, Liwei Liu, Gui-Bin Liu, Weida Hu, Yanfeng Gao, Haitao Yang, Weibo Gao, Li Lu, Yeliang Wang, Kazu Suenaga, Guangtong Liu, Feng Ding, Yugui Yao and Zheng Liu "Composition and phase engineering of metal chalcogenides and phosphorous chalcogenides." Nature Materials (2022): 1-9. 
[12] Bijun Tang, Xiaowei Wang, Mengjiao Han, Xiaodong Xu, Zhaowei Zhang, Chao Zhu, Xun Cao, Yumeng Yang, Qundong Fu, Jianqun Yang, Xingji Li, Weibo Gao, Jiadong Zhou, Junhao Lin, Zheng Liu. "Phase engineering of Cr5Te8 with colossal anomalous Hall effect." Nature Electronics 5.4 (2022): 224-232.
[13] Cong Wang, Rui-Chun Xiao, Huiying Liu, Zhaowei Zhang, Shen Lai, Chao Zhu, Hongbing Cai, Naizhou Wang, Shengyao Chen, Ya Deng, Zheng Liu, Shengyuan A Yang, Wei-bo Gao. " Room temperature third-order nonlinear Hall effect in Weyl semimetal TaIrTe4". National Science Review, 2022.
[14] Chongyun Jiang, Abdullah Rasmita, Hui Ma, Qinghai Tan, Zhaowei Zhang, Zumeng Huang, Shen Lai, Naizhou Wang, Sheng Liu, Xue Liu, Ting Yu, Qihua Xiong, Wei-bo Gao. "Room-temperature gate-tunable bipolar valley Hall effect in MoS2/WSe2 heterostructures". Nature Electronics, 5, 23–27 (2022).
[15] Anyuan Gao, Yu-Fei Liu, Chaowei Hu, Jian-Xiang Qiu, Christian Tzschaschel, Barun Ghosh, Sheng-Chin Ho, Damien Bérubé, Rui Chen, Haipeng Sun, Zhaowei Zhang, Xin-Yue Zhang, Yu-Xuan Wang, Naizhou Wang, Zumeng Huang, Claudia Felser, Amit Agarwal, Thomas Ding, Hung-Ju Tien, Austin Akey, Jules Gardener, Bahadur Singh, Kenji Watanabe, Takashi Taniguchi, Kenneth S Burch, David C Bell, Brian B Zhou, Weibo Gao, Hai-Zhou Lu, Arun Bansil, Hsin Lin, Tay-Rong Chang, Liang Fu, Qiong Ma, Ni Ni, Su-Yang Xu. "Layer Hall effect in a 2D topological axion antiferromagnet." Nature 595.7868 (2021): 521-525.
[16] Shen Lai, Huiying Liu, Zhaowei Zhang, Jianzhou Zhao, Xiaolong Feng, Naizhou Wang, Chaolong Tang, Yuanda Liu, KS Novoselov, Shengyuan A Yang, Wei-bo Gao. "Third-order nonlinear Hall effect induced by the Berry-connection polarizability tensor. " Nature Nanotechnology, 16(8), 869-873 (2021).
[17] Jiadong Zhou, Junhao Lin, Hunter Sims, Chongyun Jiang, Chunxiao Cong, John A Brehm, Zhaowei Zhang, Lin Niu, Yu Chen, Yao Zhou, Yanlong Wang, Fucai Liu, Chao Zhu, Ting Yu, Kazu Suenaga, Rohan Mishra, Sokrates T Pantelides, Zhen‐Gang Zhu, Weibo Gao, Zheng Liu, Wu Zhou. "Synthesis of Co-Doped MoS2 Monolayers with Enhanced Valley Splitting." Advanced Materials 32 (11), 1906536
[18] Chaolong Tang, Zhaowei Zhang, Shen Lai, Qinghai Tan, Weibo Gao. "Magnetic Proximity Effect in 2D Ferromagnetic CrBr3/Graphene van der Waals Heterostructures." Advanced Materials 32 (16), 1908498
[19] Tong Li, Yanhao Xu, Zhaowei Zhang, Zhuoxi Liang, Omololu Odunmbaku, Xiaoyan Huang, Filippo S Boi, Sijie Zhang, Yong Liu, Jiqiu Wen, Tian Yu. "Self-Assembly Prepared Millimeter Length Ferromagnetic Carbon Nanotubes with Spin Nontrivial Electronic Transport Properties. " ACS Applied Electronic Materials, 2(2), 491-498.
[20] Tian Yu, Zhaowei Zhang, Yanhao Xu, Y Liu, Wenjing Li, Ya Nie, Xi Zhang, Gang Xiang. "Exchange bias coupling in NiO/Ni bilayer tubular nanostructures synthetized by electrodeposition and thermal oxidation." Journal of Magnetism and Magnetic Materials 429 (2017): 74-78. 

