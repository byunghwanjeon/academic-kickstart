---
title: "Coronary luminal and wall mask prediction using convolutional neural network"
date: 2017-04-01
publishDate: 2020-03-03T09:58:07.972898Z
authors: ["Y. Hong", "Y-M. Hong", "Y. Jang", "S. Kim", "B. Jeon", "S. Jung", "S. Ha", "D. Han", "H. Shim", "H. J. Chang"]
publication_types: ["1"]
abstract: "A significant amount of research has been done on the segmentation of coronary arteries. However, the resulting automated boundary delineation is still not suitable for clinical utilization. The convolutional neural network was driving advances in the medical image processing. We propose the brief convolutional network (BCN) that automatically produces the labeled mask with the luminal and wall boundaries of the coronary artery. We utilized 50 patients of CCTA - intravascular ultrasound matched image data sets. Training and testing were performed on 40 and 10 patient data sets, respectively. The prediction of luminal and wall mask was performed using stacked BCN on the each image view: axial, coronal, and sagittal of straightened curved planar reformation. We defined the vector that includes probability from BCN result on each image view and proposed amplified probability. We used an Adaptive Boost regressor with an extremely randomized tree regressor to determine the label for unknown probability vector."
featured: false
publication: "*2017 IEEE 14th International Symposium on Biomedical Imaging (ISBI 2017)*"
tags: ["Coronary artery", "Deep learning", "Image segmentation", "adaptive boost regressor", "Arteries", "biomedical ultrasonics", "blood vessels", "brief convolutional network", "cardiology", "CCTA-intravascular ultrasound image", "Classification", "Computer architecture", "convolutional neural network", "Convolutional neural network", "coronary artery segmentation", "coronary luminal", "coronary wall mask prediction", "extremely randomized tree regressor", "Feature extraction", "image segmentation", "image view", "learning (artificial intelligence)", "medical image processing", "neural nets", "Neural networks", "Plaque quantification", "probability", "regression analysis", "Training", "Ultrasonic imaging"]
doi: "10.1109/ISBI.2017.7950696"
image:
  caption: "The overall process for the target mask training using the proposed BCN architecture."
  focal_point: "center"
  preview_only: false
---
The BCN architecture was stacked to be utilized as a convolutional auto-encoder and image and mask pair-wise training method.
