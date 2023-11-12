# Fungi Identification
## classifying microscopic images of fungi using CNN's

This is a straightforward application of convolutional neural networks to image classification.  It uses [the DeFungi dataset](https://archive.ics.uci.edu/dataset/773/defungi) from the UC Irvine Machine Learning Repository.  Data consist of 9114 images of microscopic photographs of fungi divided into five different types.  They have already been algorithmically cropped.

Computer-aided identification of fungal pathogens using neural networks could be a substantial aid in diagnosis.  It’s also reasonable to suppose that trained models may be extensible to other mycological problems. 

The [original study](https://arxiv.org/abs/2109.07322) managed to attain a 73% accuracy rate with Inception V3 trained from scratch, and 85% accuracy using transfer learning with VGG16.  In this notebook, I'm going to start by building some CNN's from the ground up, using Keras, and then deploy some established image recognition tools.

