---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Nonparametric inference of the hemodynamic response using multi-subject fMRI
  data
subtitle: ''
summary: ''
authors:
- Tingting Zhang
- Fan Li
- Lane Beckes
- Casey L. Brown
- James A. Coan
tags:
- '"Bias correction"'
- '"General linear model"'
- '"Hemodynamic response function"'
- '"Kernel smoothing"'
- '"Regularization"'
- '"fMRI"'
- '"neuroimaging"'
- '"brain"'
- '"neural"'
categories: []
date: '2012-11-01'
lastmod: 2020-11-24T18:24:19-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-11-24T23:24:19.411668Z'
publication_types:
- '2'
abstract: Estimation and inferences for the hemodynamic response functions (HRF) using
  multi-subject fMRI data are considered. Within the context of the General Linear
  Model, two new nonparametric estimators for the HRF are proposed. The first is a
  kernel-smoothed estimator, which is used to construct hypothesis tests on the entire
  HRF curve, in contrast to only summaries of the curve as in most existing tests.
  To cope with the inherent large data variance, we introduce a second approach which
  imposes Tikhonov regularization on the kernel-smoothed estimator. An additional
  bias-correction step, which uses multi-subject averaged information, is introduced
  to further improve efficiency and reduce the bias in estimation for individual HRFs.
  By utilizing the common properties of brain activity shared across subjects, this
  is the main improvement over the standard methods where each subject's data is usually
  analyzed independently. A fast algorithm is also developed to select the optimal
  regularization and smoothing parameters. The proposed methods are compared with
  several existing regularization methods through simulations. The methods are illustrated
  by an application to the fMRI data collected under a psychology design employing
  the Monetary Incentive Delay (MID) task. © 2012 Elsevier Inc.
publication: '*NeuroImage*'
doi: 10.1016/j.neuroimage.2012.08.014
---
