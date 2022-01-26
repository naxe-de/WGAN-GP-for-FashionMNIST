# WGAN-GP for FashionMNIST

## Description:
The goal of this project was to train a Wasserstein GAN with Gradient Penalty (WGAN-GP) with the FashionMNIST repository by Zalando Research. The WGAN code is based on the coursera.org course on Generative Adverserial Networks by deeplearning.ai with some modifications to fit the purpose.

### Participants:
Nils Axe

### Contact information:
naxe-de on GitHub

### Course:
Generative Adversarial Networks

### Semester:
WiSe2122

### Data
Fashion-MNIST is a dataset of Zalando's article images and consistis of two sets of 60,000 and 10,000 examples (train and test). Each example is a 28x28 grayscale image.
In this project the complete training set was used (including all classes i.e. T-shirts/tops, Trousers, Pullovers, Dresses, Coats, Sandals, Shirts, Sneakers, Bags and Ankle boots).

### Methods
The GAN in this project is augmented with Wasserstein loss as well as Gradient Penalty.

Wasserstein Loss minimizes an approximation of the Earth-Mover's distance making the GAN more resilient to mode collapse among other advantages.
Gradient Penalty adds a penalty to the gradient norm to enforce Lipschitz continuity and further improves training stability.

### Results
After only limited amount of training the GAN is able to generate considerably good examples of clothing. Especially considering the difference in classes between e.g. Trousers and Shoes.
The example pictures given in this repository stem from training on a Google Colab GPU for 3 hours.