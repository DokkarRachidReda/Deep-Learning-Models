<p align="center"><img width="40%" src="https://github.com/yunjey/pytorch-tutorial/blob/master/logo/pytorch_logo_2018.svg" /></p>
<p align="center"><img alt="Awesome Flutter" src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat" /></p>

# Deep-Learning-Models
 collection of my deep learning  models
## Resources :
* [tutorialspoint](https://www.tutorialspoint.com/) to learn Numpy Pandas ...
* [Intro to Deep Learning with PyTorch](https://classroom.udacity.com/courses/ud188) Udacity course to learn about deep learning
* [Kaggle](https://www.kaggle.com) to find datasets and challengs
* [Colab](https://colab.research.google.com) to train models in gpu for free :)
## Content :

* **Digits Recognizer** model, from 28x28x1 images (MNIST dataset), the challenge from Kaggle [digit-recognizer](https://www.kaggle.com/c/digit-recognizer)
  you can find this model in ``` ./Digits.ipynb ```
* **Titanic3 Dataset** analyse and survive prediction using MLP pytorch, I got 84% accuracy :)  .
  you can find the dataset description [here](http://campus.lakeforest.edu/frank/FILES/MLFfiles/Bio150/Titanic/TitanicMETA.pdf)
  and the dataset [here](http://biostat.mc.vanderbilt.edu/wiki/pub/Main/DataSets/titanic3.xls)
  the model is in ``` ./Titanic3.ipynb ```
  
* **Arabic Letters classifier** using pytorch (MLP), the data is 32x32x3 images
  I got 73% accuracy ;_;
  
  the CNN model on the other hand performed much better,the test accuracy is 84.9 in 36 epoch (the MLP was trained on 150 epoch)
  
  you can find the MLP model in ``` ./arabic.ipynb ```,the CNN model in ``` ./arabic_CNN.ipynb ``` and the data in ``` ./Datasets/arabic``` , the data is structred to be loaded directly   to pytorch ImageFolder Dataset
  
* **AI hack tunisia precalificacion** is a ML challenge to predict if an african have a bank account, it's also a precalificacion for AI hack tunisia,
 I got an accuracy of 99.89 %. 
 
   you can find the challenge online [here](http://zindi.africa/competitions/financial-inclusion-in-africa) 

## Contribution :
feel free to contribute or to report any error or improvment to any model, i would be happy to add your model here too :)
