# Seminar: _Business Analytics_  -  Topic: _Adversarial Attacks_: 
In this repository the corresponding __code__ and the used __example pictures__ for the seminar paper _"Adversarial Attacks"_ are located.

###  Disclaimer: 
The folder _\images_ includes all used images for the generation of Adversarial Examples.
All images were taken by myself, so no copyrights were infringed for these pictures.

### Model:

For the implementation the __Fast Gradient Sign Method (FGSM)__ by [Goodfellow et al. (2015)](https://arxiv.org/abs/1412.6572) was used, which is discussed in the corresponding seminar thesis in _chapter 5.1_.

For this purpose, several images were altered using a range of different epsilon values. The epsilon value controls the degree with which the image is to be changed. A high epsilon value increases the success rate of the Adversarial Attack, but also creates visible visual changes to the original input image for the human eye, which makes the perturbation more obvious.

Subsequently, the class percentage as output of the classification was compared with the corresponding originals. Following the success rate was determined and compared between all used sample images.

### Colab Notebook:
The corresponding notebook on Google Colab can be found [HERE]
