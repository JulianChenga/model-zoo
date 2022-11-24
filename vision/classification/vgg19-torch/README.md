<!--- CC-BY-NC 4.0 -->

# VGG19

## Description

In this work we investigate the effect of the convolutional network depth on its accuracy in the large-scale image recognition setting. Our main contribution is a thorough evaluation of networks of increasing depth using an architecture with very small (3x3) convolution filters, which shows that a significant improvement on the prior-art configurations can be achieved by pushing the depth to 16-19 weight layers. 
These findings were the basis of our ImageNet Challenge 2014 submission, where our team secured the first and the second places in the localisation and classification tracks respectively. We also show that our representations generalise well to other datasets, where they achieve state-of-the-art results. We have made our two best-performing ConvNet models publicly available to facilitate further research on the use of deep visual representations in computer vision.

## Model

VGG19

|Model        |top-1 error       |top-5 error       |
|-------------|:-----------------|:-----------------|
|VGG19        |27.62             |9.12              |

## Dataset

* Dataset used for train and validation: [ImageNet (ILSVRC2012)](http://www.image-net.org/challenges/LSVRC/2012/).

## References

* [Very Deep Convolutional Networks for Large-Scale Image Recognition](https://arxiv.org/abs/1409.1556)
* [VGG-Nets](https://pytorch.org/hub/pytorch_vision_vgg/)

## License

More specifically, SWAG models are released under the CC-BY-NC 4.0 license. See SWAG LICENSE for additional details.