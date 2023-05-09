# X-AID: Feature Attribution-based Explanation Methods for Adversarial Detection

Repository for the paper "X-AID: Feature Attribution-based Explanation Methods for Adversarial Detection" submitted at ACM CCS 2023. 

This paper provides our implmentation of various feature attribution based unsupervised adversarial detectors. We use integrated gradient method to extract various features of benign images and train three different detectors.

The directory consists of following folders: 
- Approach: This directory contains notebooks for implementation of our proposed approaches.
- Compute threshold: Based on the metrics collected using notebooks in Approach, we compute thresholds for benign images. 
- Detectors: This folder consists of implementation of two state-of-the-art unsupervised detectors: feature squeeze and MagNet. 
- Evaluate: We provide notebooks for evaluating the detectors performance on test-set. 
- Utils: We provide notebooks used for generating plots for the paper. 