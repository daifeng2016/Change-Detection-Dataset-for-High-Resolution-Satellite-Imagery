# Change-Detection-dataset-for-High-resolution-Satellite-Image
This repository is for releasing a change detection dataset for high-resolution satellite imagery.

## paper
SemiCDNet: A Semisupervised Convolutional Neural Network for Change Detection in High Resolution Remote-Sensing Images [https://ieeexplore.ieee.org/document/9161009]
## Introduction
Change detection (CD) is one of the main applications of remote sensing. With the increasing popularity of
deep learning, most recent developments of CD methods have
introduced the use of deep learning techniques to increase
the accuracy and automation level over traditional methods.
However, when using supervised CD methods, a large amount of
labeled data is needed to train deep convolutional networks with
millions of parameters. These labeled data are difficult to acquire
for CD tasks. To address this limitation, a novel semisupervised
convolutional network for CD (SemiCDNet) is proposed based
on a generative adversarial network (GAN). First, both the
labeled data and unlabeled data are input into the segmentation
network to produce initial predictions and entropy maps. Then,
to exploit the potential of unlabeled data, two discriminators
are adopted to enforce the feature distribution consistency of
segmentation maps and entropy maps between the labeled and
unlabeled data. During the competitive training, the generator is
continuously regularized by utilizing the unlabeled information,
thus improving its generalization capability. The effectiveness
and reliability of our proposed method are verified on two
high-resolution remote sensing data sets. Extensive experimental
results demonstrate the superiority of the proposed method
against other state-of-the-art approaches.
## Dataset
The proposed dataset can be found at [https://pan.baidu.com/s/12Ln-nCb15YNu1T28pzC0rA] password: 8quw

## Citation
Please cite our paper if you find it useful for your research.
