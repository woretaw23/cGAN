# cGAN

## Description
Generate MNIST digits conditioned on class labels, using the MindSpore GAN model.

## cGAN Description
Generative Adversarial Nets were recently introduced as a novel way to train generative models. In this work we introduce the conditional version of generative adversarial nets, which can be constructed by simply feeding the data, y, we wish to condition on to both the generator and discriminator. We show that this model can generate MNIST digits conditioned on class labels. We also illustrate how this model could be used to learn a multi-modal model, and provide preliminary examples of an application to image tagging in which we demonstrate how this approach can generate descriptive tags which are not part of training labels.

Paper: Conditional Generative Adversarial Nets. https://arxiv.org/pdf/1411.1784.pdf

## DATASET
Train CGAN Dataset used: MNIST
Dataset size：52.4M，60,000 28*28 in 10 classes
1. Train：60,000 images
2. Test：10,000 images
3. Data format： binary files
