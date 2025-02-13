---
title: "Zhang Lab - Publications"
layout: gridlay
excerpt: "Zhang Lab -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

## Group highlights

**At the end of this page, you can find the [full list of publications and patents](#full-list-of-publications).**

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


## Full List of publications
<em>Chuangwen Wu, Shuting Cui, Yaqin Guo, Zhaowei Zhang, Jing Zhang, Xiao Deng, Guang Zeng, Chuantong Ren, Peizhi Li, Xiangqing Zhou, Xu Zhang, Jingfeng Li, Tao Zhu, Xiufeng Han, Jinkui Zhao, Hao Wang, Yue Zhang, Shiheng Liang, Hao Wu </em> <br />
Manipulation of Unconventional Spin Polarization in Non‐Collinear Exchange‐Spring Magnetic Structures. <br />
<a href="https://advanced.onlinelibrary.wiley.com/doi/abs/10.1002/adma.202414139">Advanced Materials 37, 5, 2414139 (2025) </a> <br />
<br />

<em>Hongbing Cai, Abdullah Rasmita, Ruihua He, Zhaowei Zhang, Qinghai Tan, Disheng Chen, Naizhou Wang, Zhao Mu, John JH Eng, Yongzhi She, Nan Pan, Qian Wang, Zhaogang Dong, Xiaoping Wang, Juan Wang, Yansong Miao, Ranjan Singh, Cheng-Wei Qiu, Xiaogang Liu, Weibo Gao. </em> <br />
Charge-depletion-enhanced WSe2 quantum emitters on gold nanogap arrays with near-unity quantum efficiency. <br />
<a href="https://www.nature.com/articles/s41566-024-01460-9">Nature Photonics 18, 842–847 (2024) </a> <br />
<br />

<em>Ziqi Li, Jiayun Liu, Abdullah Rasmita, Zhaowei Zhang, Weibo Gao, Elbert EM Chia. </em> <br />
Room-Temperature Geometrical Circular Photocurrent in Few-Layer MoS2. <br />
<a href="https://pubs.acs.org/doi/abs/10.1021/acs.nanolett.4c00057">Nano Letters 24, 20, 5952–5957 (2024). </a> <br />
<br />

<em>Naizhou Wang, Daniel Kaplan, Zhaowei Zhang, Tobias Holder, Ning Cao, Aifeng Wang, Xiaoyuan Zhou, Feifei Zhou, Zhengzhi Jiang, Chusheng Zhang, Shihao Ru, Hongbing Cai, Kenji Watanabe, Takashi Taniguchi, Binghai Yan, Weibo Gao. </em> <br />
Quantum metric-induced nonlinear transport in a topological antiferromagnet.<br /> 
<a href="https://www.nature.com/articles/s41586-023-06363-3">Nature 621, 487–492 (2023).</a> <br />
<br />

<em>Naizhou Wang, Jing-Yang You, Aifeng Wang, Xiaoyuan Zhou, Zhaowei Zhang, Shen Lai, Hung-Ju Tien, Tay-Rong Chang, Yuan-Ping Feng, Hsin Lin, Guoqing Chang, Wei-bo Gao. </em> <br />
Non-centrosymmetric topological phase probed by Nonlinear Hall effect. <br />
<a href="https://academic.oup.com/nsr/advance-article/doi/10.1093/nsr/nwad103/7140549">National Science Review (2023): nwad103.</a> <br />
<br />

<em>Qinghai Tan, Abdullah Rasmita, Zhaowei Zhang, Hongbing Cai, Xiangbin Cai, Xuran Dai, Kenji Watanabe, Takashi Taniguchi, Allan H MacDonald, Weibo Gao. </em> <br />
Layer-dependent correlated phases in WSe2/MoS2 moiré superlattice. <br />
<a href="https://www.nature.com/articles/s41563-023-01521-4">Nature Materials 22, 605–611 (2023).</a> <br />
<br />

<em>Hongbing Cai, Abdullah Rasmita, Qinghai Tan, Jia-Min Lai, Ruihua He, Disheng Chen, Naizhou Wang, Zhao Mu, Zumeng Huang, Zhaowei Zhang, John JH Eng, Yuanda Liu, Yongzhi She, Nan Pan, Xiaoping Wang, Xiaogang Liu, Jun Zhang, Weibo Gao. </em> <br />
Interlayer donor-acceptor pair excitons in MoSe2/WSe2 moiré heterobilayer. <br />
<a href="https://www.nature.com/articles/s41467-023-41330-6">Nature Communications 14, 5766 (2023).</a> <br />
<br />

<em>Zhaowei Zhang, Naizhou Wang, Ning Cao, Aifeng Wang, Xiaoyuan Zhou, Kenji Watanabe, Takashi Taniguchi, Binghai Yan, and Wei-bo Gao.</em> <br />
Controlled large non-reciprocal charge transport in an intrinsic magnetic topological insulator MnBi2Te4.<br />
<a href="https://www.nature.com/articles/s41467-022-33705-y">Nature Communications, 13.1 (2022): 6191.</a> <br />
<br />

<em>Shen Lai, Zhaowei Zhang, Naizhou Wang, Abdullah Rasmita, Ya Deng, Zheng Liu, Wei-bo Gao. </em> <br />
Dual-Gate All-Electrical Valleytronic Transistors.</em> <br />
<a href="https://pubs.acs.org/doi/10.1021/acs.nanolett.2c03947">Nano Letters 23.1(2023):192-197.</a> <br />
<br />

<em>Qinghai Tan, Abdullah Rasmita, Zhaowei Zhang, KS Novoselov, Wei-bo Gao.</em> <br />
Signature of Cascade Transitions between Interlayer Excitons in a Moiré Superlattice. <br />
<a href="https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.129.247401">Physical Review Letters 192.24(2022): 247401.</a> <br />
<br />

<em>Xiaodan Lyu, Qinghai Tan, Lishu Wu, Chusheng Zhang, Zhaowei Zhang, Zhao Mu, Jesús Zúñiga-Pérez, Hongbing Cai, Weibo Gao. </em> <br />
Strain Quantum Sensing with Spin Defects in Hexagonal Boron Nitride. <br />
<a href="https://pubs.acs.org/doi/10.1021/acs.nanolett.2c01722">Nano Letters 22.16(2022) 6553-6559.</a> <br />
<br />

<em>Jiadong Zhou, Chao Zhu, Yao Zhou, Jichen Dong, Peiling Li, Zhaowei Zhang, Zhen Wang, Yung-Chang Lin, Jia Shi, Runwu Zhang, Yanzhen Zheng, Huimei Yu, Bijun Tang, Fucai Liu, Lin Wang, Liwei Liu, Gui-Bin Liu, Weida Hu, Yanfeng Gao, Haitao Yang, Weibo Gao, Li Lu, Yeliang Wang, Kazu Suenaga, Guangtong Liu, Feng Ding, Yugui Yao and Zheng Liu. </em> <br />
Composition and phase engineering of metal chalcogenides and phosphorous chalcogenides. <br />
<a href="https://www.nature.com/articles/s41563-022-01291-5">Nature Materials 22, 450–458 (2023).</a> <br />
<br />

<em>Bijun Tang, Xiaowei Wang, Mengjiao Han, Xiaodong Xu, Zhaowei Zhang, Chao Zhu, Xun Cao, Yumeng Yang, Qundong Fu, Jianqun Yang, Xingji Li, Weibo Gao, Jiadong Zhou, Junhao Lin, Zheng Liu.</em> <br />
Phase engineering of Cr5Te8 with colossal anomalous Hall effect. <br />
<a href="https://www.nature.com/articles/s41928-022-00754-6">Nature Electronics 5.4 (2022): 224-232.</a> <br />
<br />

<em>Cong Wang, Rui-Chun Xiao, Huiying Liu, Zhaowei Zhang, Shen Lai, Chao Zhu, Hongbing Cai, Naizhou Wang, Shengyao Chen, Ya Deng, Zheng Liu, Shengyuan A Yang, Wei-bo Gao. </em> <br />
Room temperature third-order nonlinear Hall effect in Weyl semimetal TaIrTe4. <br />
<a href="https://academic.oup.com/nsr/article/9/12/nwac020/6528385">National Science Review 9.12 (2022): nwac020.</a> <br />
<br />

<em>Govindan Kutty Rajendran Nair, Zhaowei Zhang, Fuchen Hou, Ali Abdelaziem, Xiaodong Xu, Steve Wu Qing Yang, Nan Zhang, Weiqi Li, Chao Zhu, Yao Wu, Heng Weiling, Lixing Kang, Teddy Salim, Jiadong Zhou, Lin Ke, Junhao Lin, Xingji Li, Weibo Gao, Zheng Liu. </em> <br />
Phase-pure two-dimensional FexGeTe2 magnets with near-room-temperature TC. <br />
<a href="https://link.springer.com/article/10.1007/s12274-021-3502-0">Nano Research 15.1 (2022): 457-464.</a> <br />
<br />

<em>Chongyun Jiang, Abdullah Rasmita, Hui Ma, Qinghai Tan, Zhaowei Zhang, Zumeng Huang, Shen Lai, Naizhou Wang, Sheng Liu, Xue Liu, Ting Yu, Qihua Xiong, Wei-bo Gao. </em> <br />
Room-temperature gate-tunable bipolar valley Hall effect in MoS2/WSe2 heterostructures. <br />
<a href="https://www.nature.com/articles/s41928-021-00686-7">Nature Electronics, 5, 23–27 (2022). </a> <br />
<br />

<em>Anyuan Gao, Yu-Fei Liu, Chaowei Hu, Jian-Xiang Qiu, Christian Tzschaschel, Barun Ghosh, Sheng-Chin Ho, Damien Bérubé, Rui Chen, Haipeng Sun, Zhaowei Zhang, Xin-Yue Zhang, Yu-Xuan Wang, Naizhou Wang, Zumeng Huang, Claudia Felser, Amit Agarwal, Thomas Ding, Hung-Ju Tien, Austin Akey, Jules Gardener, Bahadur Singh, Kenji Watanabe, Takashi Taniguchi, Kenneth S Burch, David C Bell, Brian B Zhou, Weibo Gao, Hai-Zhou Lu, Arun Bansil, Hsin Lin, Tay-Rong Chang, Liang Fu, Qiong Ma, Ni Ni, Su-Yang Xu. </em> <br />
Layer Hall effect in a 2D topological axion antiferromagnet. <br />
<a href="https://www.nature.com/articles/s41586-021-03679-w">Nature 595.7868 (2021): 521-525. </a> <br />
<br />

<em>Shen Lai, Huiying Liu, Zhaowei Zhang, Jianzhou Zhao, Xiaolong Feng, Naizhou Wang, Chaolong Tang, Yuanda Liu, KS Novoselov, Shengyuan A Yang, Wei-bo Gao. </em> <br />
Third-order nonlinear Hall effect induced by the Berry-connection polarizability tensor. <br />
<a href="https://www.nature.com/articles/s41565-021-00917-0">Nature Nanotechnology, 16(8), 869-873 (2021). </a> <br />
<br />

<em>Jiadong Zhou, Junhao Lin, Hunter Sims, Chongyun Jiang, Chunxiao Cong, John A Brehm, Zhaowei Zhang, Lin Niu, Yu Chen, Yao Zhou, Yanlong Wang, Fucai Liu, Chao Zhu, Ting Yu, Kazu Suenaga, Rohan Mishra, Sokrates T Pantelides, Zhen‐Gang Zhu, Weibo Gao, Zheng Liu, Wu Zhou. </em> <br />
Synthesis of Co-Doped MoS2 Monolayers with Enhanced Valley Splitting. <br />
<a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/adma.201906536">Advanced Materials 32 (11), 1906536. </a>  <br />
<br />

<em>Chaolong Tang, Zhaowei Zhang, Shen Lai, Qinghai Tan, Weibo Gao. </em> <br />
Magnetic Proximity Effect in 2D Ferromagnetic CrBr3/Graphene van der Waals Heterostructures. <br />
<a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/adma.201908498">Advanced Materials 32 (16), 1908498. </a>  <br />
<br />

<em>Tong Li, Yanhao Xu, Zhaowei Zhang, Zhuoxi Liang, Omololu Odunmbaku, Xiaoyan Huang, Filippo S Boi, Sijie Zhang, Yong Liu, Jiqiu Wen, Tian Yu. </em> <br />
Self-Assembly Prepared Millimeter Length Ferromagnetic Carbon Nanotubes with Spin Nontrivial Electronic Transport Properties. <br />
<a href="https://pubs.acs.org/doi/10.1021/acsaelm.9b00723">ACS Applied Electronic Materials, 2(2), 491-498. </a>  <br />
<br />

<em>Zhaowei Zhang, Jingzhi Shang, Chongyun Jiang, Abdullah Rasmita, Weibo Gao, Ting Yu. </em> <br />
Direct photoluminescence probing of ferromagnetism in monolayer two-dimensional CrBr3. <br />
<a href="https://pubs.acs.org/doi/abs/10.1021/acs.nanolett.9b00553">Nano Letters (2019) 5: 3138-3142.</a> <br />
<br />

<em>Tian Yu, Zhaowei Zhang, Yanhao Xu, Y Liu, Wenjing Li, Ya Nie, Xi Zhang, Gang Xiang. </em> <br />
Exchange bias coupling in NiO/Ni bilayer tubular nanostructures synthetized by electrodeposition and thermal oxidation.  <br />
<a href="https://www.sciencedirect.com/science/article/abs/pii/S0304885316325124?via%3Dihub">Journal of Magnetism and Magnetic Materials 429 (2017): 74-78. </a>  <br />
<br />

## Patents
<em>余天, 张兆伟, 徐延浩, 申康琦, 辛晨, 刘雨果, 潘锐, 向钢, 张析</em><br />
磁性薄膜结构及其制造、使用方法和磁敏传感单元、阵列 <br />
CN105449096B <br />
<br />
<em>余天, 徐延浩, 张兆伟</em><br />
磁性薄膜结构以及含有其的磁敏传感器器件、应用方法 <br />
CN106597102B <br />
<br />
