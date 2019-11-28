# Seminar: _Business Analytics_ 
# - Topic: _Adversarial Attacks_: 
In this repository the corresponding __code__ and the used __example pictures__ for the seminar paper _"Adversarial Attacks"_ are located.

###  Disclaimer: 
The folder _\data_ includes all used example images used for Adversarial Example generation.
All images were taken by myself, so no copyrights were infringed for these pictures.

### Model:

For the implementation of a model the The Fast Gradient Sign Method (FGSM) by [Goodfellow et al. (2015)](https://arxiv.org/abs/1412.6572) was chosen, which is discussed in the corresponding seminar paper in chapter 5.1.

For this purpose, several images were altered using a range of different epsilon values. Subsequently, the output of the classification was compared with the corresponding originals and the success rate was determined.
