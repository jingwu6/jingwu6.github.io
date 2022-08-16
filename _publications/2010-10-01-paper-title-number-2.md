---
title: "Extended Agriculture-Vision: An Extension of a Large Aerial Image Dataset for Agricultural Pattern Analysis"
permalink: /publication/2010-10-01-paper-title-number-2
date: 2022-08-15
excerpt: '**Jing Wu**, David Pichler, Daniel Marley, Naira Hovakimyan, Jennifer Hobbs'
venue: 'In Submission of TMLR,'
paperurl: 'https://github.com/jingwu6/jingwu6.github.io/blob/master/files/AG%2B.pdf'
---

**Abstract** \
A key challenge for much of the machine learning work on remote sensing and earth observation data is the difficulty in acquiring large amounts of accurate labeled data. This is particularly true for semantic segmentation tasks, which are much less common in the remote sensing domain because of incredible difficulty in collecting precise, accurate, pixel-level annotations at scale. Recent efforts have addressed these challenges both through the creation of supervised datasets as well as the application of self-supervised methods.We continue these efforts on both fronts. First, we generate and release an improved version of the Agriculture-Vision dataset to include raw, full-field imagery for greater experimental flexibility. Second, we extend this dataset with the release of 3600 large, high-resolution (10cm/pixel), full-field, red-green-blue and near-infrared images for pre-training. Third, we incorporate the Pixel-to-Propagation Module originally built on the SimCLR framework into the framework of MoCo-V2. Finally, we demonstrate the usefulness of this data by benchmarking different contrastive learning approaches on both downstream classification and semantic segmentation tasks. We explore both CNN and Swin Transformer architectures within different frameworks based on MoCo-V2. Together, these approaches enable us to better detect key agricultural patterns of interest across a field from aerial imagery so that farmers may be alerted to problematic areas in a timely fashion to inform their management decisions. Furthermore, the release of these datasets will support numerous avenues of research for computer vision in remote sensing for agriculture. 
