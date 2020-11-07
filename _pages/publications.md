---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
All Publications
======
E.Kim, J.Yarnall, P.Shah, G.Kenyon, "A Neuromorphic Sparse Coding Defense to Adversarial Images", International Conference on Neuromorphic Systems, ICONS, 2019 [PDF](http://edwardkim.net/files/sparsecodingdefense.pdf).

E.Kim, E.Lawson, K.Sullivan, G.Kenyon, "Spatiotemporal Sequence Memory for Prediction using Deep Sparse Coding", Neuro-inspired Computational Elements Workshop, NICE, 2019 [PDF](http://edwardkim.net/files/nice2019.pdf)

J.Springer, C.Strauss, A.Thresher, E.Kim, G.Kenyon, "Classifiers Based on Deep Sparse Coding Architectures are Robust to Deep Learning Transferable Examples", arXiv:1811.07211, 2018 [PDF](https://arxiv.org/pdf/1811.07211).

E.Kim, K.McCoy, "Multimodal Deep Learning using Images and Text for Information Graphic Classification", ACM SIGACCESS Conference on Computers and Accessibility, Assets, 2018. (Best Paper Nominee) [PDF](https://dl.acm.org/ft_gateway.cfm?id=3236357&amp;ftid=2007840&amp;dwn=1&amp;CFID=84123166&amp;CFTOKEN=f4766feba2bdcd0b-BE597719-C974-B1FF-A633D11E8D8A3ED3)

E.Kim, D.Hannan, G.Kenyon, "Deep Sparse Coding for Invariant Multimodal Halle Berry Neurons", International Conference on Computer Vision and Pattern Recognition, CVPR, 2018. [PDF](https://arxiv.org/abs/1711.07998)

Recent Publications 
======

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


