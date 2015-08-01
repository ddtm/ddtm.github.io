<h3 class="page-header">About</h3>

I am a PhD candidate at [Skoltech](http://www.skoltech.ru/en), advised by 
[Victor Lempitsky](http://sites.skoltech.ru/compvision/members/vilem/).
My scientific interests span computer vision and machine learning. Nowadays
I'm mostly working on __artificial neural networks__.

~~You can find my working place at the 6th floor of the
[Hypercube](http://community.sk.ru/innograd/hypercube/).~~

If you really want to, you can access my typed [curriculum vitae](./media/cv2.pdf), 
although I tend to update the <a href="http://linkedin.com/in/yganin/">LinkedIn</a> 
<a href="http://linkedin.com/in/yganin/"><i class="fa fa-linkedin-square fa-lg"></i></a>
profile more frequently. 

Here is how you would contact me:
<a href="mailto:ganin@skoltech.ru"><i class="fa fa-at fa-lg"></i></a>

<h3 class="page-header">Projects</h3>

### 2015

{% capture project_title %}
Unsupervised Domain Adaptation by Backpropagation
{% endcapture %}
{% capture project_authors %}
__Yaroslav Ganin__, Victor Lempitsky
{% endcapture %}

{% capture project_img_path %}./images/deep_da/teaser.png{% endcapture %}
{% capture project_pdf %}http://sites.skoltech.ru/compvision/projects/grl/files/paper.pdf{% endcapture %}
{% capture project_code %}https://github.com/ddtm/caffe/tree/grl{% endcapture %}
{% capture project_moar_btns %}
project page|http://sites.skoltech.ru/compvision/projects/grl/
{% endcapture %}
{% capture project_desc %}
Deep neural networks can be adapted for the new domains by incorporating 
unlabeled data into the learning procedure. Very easy to implement, yet 
gives a state-of-the-art results on the 
<a href="http://www.cs.uml.edu/~saenko/projects.html#data">Office dataset</a> 
and several other benchmarks.

Accepted to __ICML'15__.
{% endcapture %}
{% include project.html %}

{% capture project_title %}
Speeding-up Convolutional Neural Networks Using Fine-tuned CP-Decomposition
{% endcapture %}
{% capture project_authors %}
Vadim Lebedev, __Yaroslav Ganin__, Maksim Rakhuba, Ivan Oseledets, Victor Lempitsky
{% endcapture %}

{% capture project_img_path %}./images/cp_decomp/teaser.png{% endcapture %}
{% capture project_pdf %}http://arxiv.org/pdf/1412.6553v3{% endcapture %}
{% capture project_arxiv %}http://arxiv.org/abs/1412.6553{% endcapture %}
{% capture project_code %}https://github.com/vadim-v-lebedev/cp-decomposition{% endcapture %}
{% capture project_moar_btns %}
project page|http://sites.skoltech.ru/compvision/projects/speeding-up-cnns/
{% endcapture %}
{% capture project_desc %}
We propose a simple two-step approach for speeding up convolution layers within 
large convolutional neural networks based on tensor decomposition and discriminative fine-
tuning.

Accepted to __ICRL'15__.
{% endcapture %}
{% include project.html %}

### 2014

{% capture project_title %}
$ N^4 $-Fields: Neural Network Nearest Neighbor Fields for Image Transforms
{% endcapture %}
{% capture project_authors %}
__Yaroslav Ganin__, Victor Lempitsky
{% endcapture %}

{% capture project_img_path %}./images/n4/teaser.png{% endcapture %}
{% capture project_arxiv %}http://arxiv.org/abs/1406.6558{% endcapture %}
{% capture project_pdf %}./media/n4_accv2014.pdf{% endcapture %}
{% capture project_moar_btns %}
project page|http://sites.skoltech.ru/compvision/projects/n4/
{% endcapture %}
{% capture project_desc %}
__N__eural __N__etworks and __N__earest __N__eighbours search (hence
$ N^4 $) fused together to form a general
approach for solving such tasks as edge detection and segmentation 
(probably some others too).

Accepted for an oral presentation at __ACCV'14__ (_4% acceptance rate_).
{% endcapture %}
{% include project.html %}

### 2012

{% capture project_title %}
Efficient Segmentation Trees on the GPU
{% endcapture %}
{% capture project_authors %}
__Yaroslav Ganin__
{% endcapture %}

{% capture project_img_path %}./images/seg_trees/teaser2.png{% endcapture %}
{% capture project_arxiv %}{% endcapture %}
{% capture project_pdf %}
http://developer.download.nvidia.com/GTC/PDF/GTC2012/Posters/P0496_Efficient_Segmentation_Trees_by_Ganin.pdf
{% endcapture %}
{% capture project_desc %}
Here's how one may get a segmentation tree via 
[Borůvka's MST algorithm](http://en.wikipedia.org/wiki/Bor%C5%AFvka%27s_algorithm). 
No wheels were reinvented in the making of this project. 
Pure [Thrust](http://thrust.github.io/) (well, almost).

Accepted for a poster presentation at __GTC'12__.

You can find the code in the 
[CUDA Toolkit bundle](http://docs.nvidia.com/cuda/cuda-samples/index.html#cuda-segmentation-tree-thrust-library).
{% endcapture %}
{% include project.html %}

### Older projects

Here are some older projects that I was working on during my studies at
[MSU](http://www.msu.ru/en/):

* [Semantic decomposition using segmentation trees](./media/yganin_thesis_2011.pdf). 
  Specialist's thesis (__in Russian__), 2011
* [Semantic segmentation using machine learning](./media/yganin_cw_2010.pdf). 
  Coursework, 2010

<h3 class="page-header">Teaching</h3>

I was a TA for the following classes:

* __Systems Optimization__ (Skoltech, fall 2013)
* __Deep Learning__ (Yandex School of Data Analysis, spring 2015)
* __Deep Learning__ (Skoltech, spring 2015)

<h3 class="page-header">Other stuff</h3>

Currently, I am doing my internship at __Google__ (Machine Intelligence team), 
in Z&uuml;rich, for a period of 4 months, starting June 1st.
