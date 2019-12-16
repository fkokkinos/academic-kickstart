---
title: "Iterative Joint Image Demosaicking and Denoising Using a Residual Denoising Network"
date: 2019-08-01
publishDate: 2019-11-26T11:15:33.478384Z
authors: ["F. Kokkinos", "S. Lefkimmiatis"]
publication_types: ["2"]
abstract: "Modern digital cameras rely on the sequential execution of separate image processing steps to produce realistic images. The first two steps are usually related to denoising and demosaicking, where the former aims to reduce noise from the sensor and the latter converts a series of light intensity readings to color images. Modern approaches try to jointly solve these problems, i.e., joint denoising-demosaicking, which is an inherently ill-posed problem given that two-thirds of the intensity information is missing and the rest is perturbed by noise. While there are several machine learning systems that have been recently introduced to solve this problem, the majority of them rely on generic network architectures, which do not explicitly consider the physical image model. In this paper, we propose a novel algorithm that is inspired by powerful classical image regularization methods, large-scale optimization, and deep learning techniques. Consequently, our derived iterative optimization algorithm, which involves a trainable denoising network, has a transparent and clear interpretation compared with other black-box data driven approaches. Our extensive experimentation line demonstrates that our proposed method outperforms any previous approaches for both noisy and noise-free data across many different datasets. This improvement in reconstruction quality is attributed to the rigorous derivation of an iterative solution and the principled way we design our denoising network architecture, which as a result requires fewer trainable parameters than the current state-of-the-art solution, and furthermore can be efficiently trained by using a significantly smaller number of training data than existing deep demosaicking networks."
featured: false
publication: "*IEEE Transactions on Image Processing*"
url_pdf: "https://arxiv.org/pdf/1807.06403.pdf"
url_code: "https://github.com/cig-skoltech/deep_demosaick"
url_Project: "https://cig.skoltech.ru/deep_demosaick/"
doi: "10.1109/TIP.2019.2905991"
---
