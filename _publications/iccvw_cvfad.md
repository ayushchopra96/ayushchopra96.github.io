---
title: "Powering Virtual Try-On via Auxiliary Human Segmentation Learning"
collection: publications
permalink: /publications/iccvw_cvfad
venue: "Workshop on Computer Vision for Fashion, Art and Design, IEEE/CVF International Conference on Computer Vision (ICCV)"
date: 2019-10-7
<!-- citation: 'Swaminathan Gurumurthy, <b>Lantao Yu</b>, Chenyan Zhang, Yongchao Jin, Weiping Li, Xiaodong Zhang, Fei Fang. <i>ACM SIGCAS Conference on Computing and Sustainable Societies.</i> <b>COMPASS 2018</b>. -->'
---
[[PDF]](http://openaccess.thecvf.com/content_ICCVW_2019/papers/CVFAD/Ayush_Powering_Virtual_Try-On_via_Auxiliary_Human_Segmentation_Learning_ICCVW_2019_paper.pdf)
## Abstract
Image-based virtual try-on for fashion has gained considerable attention recently. This task requires to fit an inshop cloth image on a target model image. An efficient framework for this is composed of two stages: (1) warping the try-on cloth to align with the body shape and pose of the target model, and (2) an image composition module to seamlessly integrate the warped try-on cloth onto the target model image. Existing methods suffer from artifacts and distortions in their try-on output. In this work, we propose to use auxiliary learning to power an existing state-of-theart virtual try-on network. We leverage prediction of human semantic segmentation (of the target model wearing the tryon cloth) as an auxiliary task and show that it allows the network to better model the bounds of the clothing item and human skin, thereby producing a better fit. Using exhaustive qualitative and quantitative evaluation we show that there is a significant improvement in the preservation of characteristics of the cloth and person in the final try-on result, thereby outperforming the existing state-of-the-art virtual try-on framework.
