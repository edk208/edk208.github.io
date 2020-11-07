---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
All Publications
======
J. Carter, J. Rego, D. Schwartz, V. Bhandawat, and E. Kim. ”Learning Spiking Neural Network Models of Drosophila Olfaction.” In International Conference on Neuromorphic Systems, ICONS pp. 1-5. 2020 [PDF](http://edwardkim.net/files/icons2020-17.pdf).

E.Kim, J. Rego, Y. Watkins, G. Kenyon, “Modeling Biological Immunity to Adversarial Examples”, In IEEE Computer Society Conf. Computer Vision and Pattern Recognition, CVPR 2020 [PDF](http://edwardkim.net/files/07828.pdf)

Y. Watkins, E.Kim, A. Sornborger, G. Kenyon, “Using Sinusoidally-Modulated Noise as a Surrogate for Slow-Wave Sleep to Accomplish Stable Unsupervised Dictionary Learning in a Spike-Based Sparse Coding Models”, In IEEE Computer Society Conf. Computer Vision and Pattern Recognition Workshops, CVPR-W 2020 [PDF](http://edwardkim.net/files/63.pdf).

J. Marharjan, B. Mitchell, V.W.S. Chan, E.Kim,“Guided Ultrasound Imaging using a Deep Regression Network”, In Ultrasonic Imaging and Tomography, SPIE Medical Imaging, 2020 [PDF](http://edwardkim.net/files/Guided_Ultrasound_Imaging_using_a_Deep_Regression_Network_Full_Paper.pdf).

E.Kim, J.Yarnall, P.Shah, G.Kenyon, "A Neuromorphic Sparse Coding Defense to Adversarial Images", International Conference on Neuromorphic Systems, ICONS, 2019 [PDF](http://edwardkim.net/files/sparsecodingdefense.pdf).

E.Kim, E.Lawson, K.Sullivan, G.Kenyon, "Spatiotemporal Sequence Memory for Prediction using Deep Sparse Coding", Neuro-inspired Computational Elements Workshop, NICE, 2019 [PDF](http://edwardkim.net/files/nice2019.pdf)

J.Springer, C.Strauss, A.Thresher, E.Kim, G.Kenyon, "Classifiers Based on Deep Sparse Coding Architectures are Robust to Deep Learning Transferable Examples", arXiv:1811.07211, 2018 [PDF](https://arxiv.org/pdf/1811.07211).

E.Kim, K.McCoy, "Multimodal Deep Learning using Images and Text for Information Graphic Classification", ACM SIGACCESS Conference on Computers and Accessibility, Assets, 2018. (Best Paper Nominee) [PDF](https://dl.acm.org/ft_gateway.cfm?id=3236357&amp;ftid=2007840&amp;dwn=1&amp;CFID=84123166&amp;CFTOKEN=f4766feba2bdcd0b-BE597719-C974-B1FF-A633D11E8D8A3ED3)

E.Kim, D.Hannan, G.Kenyon, "Deep Sparse Coding for Invariant Multimodal Halle Berry Neurons", International Conference on Computer Vision and Pattern Recognition, CVPR, 2018. [PDF](https://arxiv.org/abs/1711.07998)

E.Kim, S. Mente, A. Keenan, V. Gehlot,“Digital Pathology Data for Improved Deep Neural Network Classification”, In Imaging Informatics for Healthcare, Research, and Applications, SPIE Medical Imaging, 2017 [PDF](http://edwardkim.net/files/spie2017finalr.pdf).

E.Kim, C.Moritz,“Enhancing the Communication Spectrum in Collaborative Virtual Environments”, In 12th International Symposium on Visual Computing, ISVC, 2016 [PDF](http://edwardkim.net/files/final_887_reduced.pdf).

E.Kim, S. Vangala,“Deep Action Unit Classification using a Binned Intensity Loss and Semantic Context Model”, In 23rd International Conference on Pattern Recognition, ICPR, 2016 [PDF](http://edwardkim.net/files/icpr2016.pdf).

E.Kim, S. Vangala,“Vinereactor: Crowdsourced Spontaneous Facial Expression Data”, In International Conference on Multimedia Retrieval, ICMR, 2016 [PDF](http://vinereactor.org/final_icmr2016_r.pdf).

E.Kim, M. Corte-Real, Z.Baloch,“A Deep Semantic Mobile Application for Thyroid Cytopathololgy”, In SPIE Medical Imaging 2016: Advanced-PACS-based Imaging Informatics and Therapeutic Applications, 2016 [PDF](http://edwardkim.net/files/fullpaper2016.pdf).

T.Xu, E.Kim, and X.Huang, “Adjustable AdaBoost Classifier and Pyramid Features for Image-based Cervical Cancer Diagnosis”, In International Symposium on Biomedical Imaging, ISBI 2015 [PDF](http://edwardkim.net/files/ISBImanuscript.pdf).

Recent Publications 
======

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


