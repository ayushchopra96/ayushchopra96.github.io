---
#title: "Powering Robust Fashion Retrieval with Information Rich Feature Embeddings"
title: "SieveNet: A Unified Framework for Robust Image-Based Virtual Try-On"
collection: publications
permalink: /publications/vitonwacv
venue: "IEEE Winter on Applications of Computer Vision (WACV)"
date: 2020-10-7
<!-- citation: 'Swaminathan Gurumurthy, <b>Lantao Yu</b>, Chenyan Zhang, Yongchao Jin, Weiping Li, Xiaodong Zhang, Fei Fang. <i>ACM SIGCAS Conference on Computing and Sustainable Societies.</i> <b>COMPASS 2018</b>. -->'
---
[[PDF]](http://openaccess.thecvf.com/content_WACV_2020/papers/Jandial_SieveNet_A_Unified_Framework_for_Robust_Image-Based_Virtual_Try-On_WACV_2020_paper.pdf)

## Abstract
Image-based virtual try-on for fashion has gained considerable attention recently. The task requires trying on a clothing item on a target model image. An efficient framework for this is composed of two stages: (1) warping (transforming) the try-on cloth to align with the pose and shape of the target model, and (2) a texture transfer module to seamlessly integrate the warped try-on cloth onto the target model image. Existing methods suffer from artifacts and
distortions in their try-on output. In this work, we present SieveNet, a framework for robust image-based virtual try-on. Firstly, we introduce a multi-stage coarse-to-fine warping network to better model fine-grained intricacies (while transforming the try-on cloth) and train it with a novel perceptual geometric matching loss. Next, we introduce a try-on cloth conditioned segmentation mask prior to improve the texture transfer network. Finally, we also introduce a dueling triplet loss strategy for training the texture translation network which further improves the quality of the generated try-on results. We present extensive qualitative and quantitative evaluations of each component of the proposed pipeline and show significant performance improvements against the current state-of-the-art methods.
