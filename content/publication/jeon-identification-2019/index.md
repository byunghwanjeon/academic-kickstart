---
title: "Identification of coronary arteries in CT images by Bayesian analysis of geometric relations among anatomical landmarks"
date: 2019-12-01
publishDate: 2020-03-03T09:58:07.950955Z
authors: ["Byunghwan Jeon", "Yeonggul Jang", "Hackjoon Shim", "Hyuk-Jae Chang"]
publication_types: ["2"]
abstract: "We propose a robust method for the identification of coronary arteries in computed tomography angiography (CTA) images. Utilizing geometric relations among the target and reference objects, which are assumed to follow a Gaussian distribution, an anatomic and geometric model is designed by Bayesian inference, which provides robust geometric priors for the target object localization. As a prerequisite process for the identification of coronary arteries, partially broken coronary artery segments found in CTA images are grouped and reconnected by geometric analysis of higher order curves connecting the broken segments. The geometric properties such as curvature and torsion represent naturalness and consistency between the vessel segments. As a problem to identify coronary arteries from CTA images, we demonstrate the robustness and accuracy of the proposed method in comparison with existing methods including commercial workstations on a variety of CTA cases."
featured: true
publication: "*Pattern Recognition*"
tags: ["Bayesian", "Computed tomography angiography", "Coronary artery", "Curvature and torsion", "Curve analysis", "Localization", "Multiple target"]
url_pdf: "http://www.sciencedirect.com/science/article/pii/S0031320319302559"
doi: "10.1016/j.patcog.2019.07.003"

image: "PR_2019_image.jpg"
  placement: 1
  caption: "The process for coronary artery identification. (a) The original image I. (b) The vesselness map V found by applying the method in [13] to I. (c) Connected component analysis (CCA) is applied to V, grouping and labeling all the vessel-like objects in the volume as candidates for the main coronary artery. (d) The average color map of the posterior probability (Eq. (1)) on the vessel-like candidates for the selection of one target segment. (e) The highest posterior probability on the right coronary artery (RCA) segment. (f) The highest posterior probability on the left coronary artery (LCA) segment."
  focal_point: "Center"
  preview_only: false
---

