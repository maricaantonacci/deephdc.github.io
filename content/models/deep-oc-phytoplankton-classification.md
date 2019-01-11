---
Title: DEEP OC Phytoplankton (Theano)
Date: 2018-09-5
Category: models, library/theano, library/lasagne, docker
GitHub: https://github.com/indigo-dc/phytoplankton-classification-theano
DockerHub: deephdc/deep-oc-phytoplankton-classification
Training_files: https://cephrgw01.ifca.es:8080/swift/v1/plankton/
License: Apache License 2.0
Summary: A trained ResNet50 on Theano to classify phytoplankton species.
---

The deep learning revolution has brought significant advances in a number of
fields [1], primarily linked to image and speech recognition. The
standardization of image classification tasks like the [ImageNet Large Scale
Visual Recognition Challenge](http://www.image-net.org/challenges/LSVRC/) [2]
has resulted in a reliable way to compare top performing architectures.

This Docker container contains a trained Convolutional Neural network optimized
for phytoplankton species identification using images. The architecture used is a Resnet50 [5]
using Lasagne on top of Theano.

### References

[1]: Yann LeCun, Yoshua Bengio, and Geofrey Hinton. [Deep learning](https://www.cs.toronto.edu/~hinton/absps/NatureDeepReview.pdf). Nature, 521(7553):436–444, may 2015.

[2]: Olga Russakovsky et al. [ImageNet Large Scale Visual Recognition Challenge](https://arxiv.org/abs/1409.0575). International Journal of Computer Vision (IJCV), 115(3):211–252, 2015.