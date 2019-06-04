---
layout: post
title: Text-To-Image Generation using Generative Adversial Networks
abstract:  5th Semester Mini-Project under Prof. GC Nandi, IIIT Allahabad
---
- Technology Stack – Python: TensorFlow, Tensorlayer, Numpy, Scipy
- The project employs the use of Generative Adversarial Networks (GAN) to convert an input text into corresponding images.
- The model was trained on VGG Flowers and UCSD Birds dataset. Also, every image has 10 captions each, relating to corresponding image in the dataset.
- The text was converted into feature vectors using LSTM Embeddings. They were concatenated with images and were feed on to the network.
- The model used Adam Optimizer to optimize the cost function of the Generative Network.