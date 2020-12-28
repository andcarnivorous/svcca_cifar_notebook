# Comparing DNN's Activations without Diagnostic Classifiers

In this/these notebook/s I will add some small experiments using different tools to calculate similarity between activations of deep neural networks. 
The reason for using methods alternative to diagnostic classifiers is that most of these allow to easily compare activations of layers with different shapes, or even layers of different models trained on different data.
This allows to test hypothesis in a way which is not possible to test by using diagnostic classifiers by, for example, testing similarity between layers of two models trained on different levels of abstraction (a language model vs. a POS-tagger, a CIFAR classifier vs. a simple shape classifier).

## Modules needed:

A couple of modules are used which are not included in this repo (for SVCCA and CKA). They can be downloaded from the links provided in the notebook/s.
