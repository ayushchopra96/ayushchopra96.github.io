---
title: "Pose Aware Fine Grained Visual Classification"
collection: publications
permalink: /publications/FGVC
venue: "25th IEEE International Conference on Image Processing"
date: 2018-10-7
<!-- citation: 'Swaminathan Gurumurthy, <b>Lantao Yu</b>, Chenyan Zhang, Yongchao Jin, Weiping Li, Xiaodong Zhang, Fei Fang. <i>ACM SIGCAS Conference on Computing and Sustainable Societies.</i> <b>COMPASS 2018</b>. -->'
---
[[PDF]](http://www.cse.iitd.ac.in/~chetan/papers/icip18-fgvc.pdf)

## Abstract
We focus on the problem of fine-grained visual classification (FGVC). We posit that unreasonable effectiveness of the state-of-the-art in this area is because of similar object cat- egories present in the ImageNet dataset, which allows such models to be pretrained on a much larger set of samples and learn generic features for those object categories. We observe an important and often ignored additional structure present in an FGVC problem: the objects are captured from a small set of viewing angles only. We notice that subtle differences be- tween object categories are difficult to pick from an arbitrary angle but easier to identify from a similar pose. We show in this paper that training specialized pose experts, focusing on classification from a single, fixed pose, and combining them in an ensemble style framework successfully exploits the structure in the problem. We demonstrate the effective- ness of the proposed approach on the benchmark Stanford Cars, FGVC-Aircrafts, and DeepFashion datasets. To high- light the contribution when the target category features may not be available in a pretrained network, we test on footwear class. We contribute a new 1000 object, 12 category footwear dataset, each object captured from 4 different poses and show significant improvement on this dataset.