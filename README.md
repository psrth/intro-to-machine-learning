# Intro to Machine Learning
The following repo contains @psrth's intro to ML projects. This repo will start off with the ACM recruitment tasks for ML/AI, but the idea is to implement all kinds of models by the end of my learning period.


## 1. K-Nearest Neighbour — MNIST Dataset
The ```knn-mnist.ipynb``` is a Jupyter Notebook with my implementation of a custom K-Nearest Neighbour algorithm to solve the [MNIST dataset](http://yann.lecun.com/exdb/mnist/). It uses the **numpy** library to handle computational stuff, but I have refrained from using either **sci-kit learn** or **panda.** 

For a value of ```k = 3```, the algorithm performed as follows:

![knn-performance](https://raw.githubusercontent.com/psrth/intro-to-machine-learning/main/imgs/knn-result.png)

You can find this project on a **Google Colab** notebook [here.](https://colab.research.google.com/drive/1C4NPNzLrBHv2VXo3STBdyJ9W-sCnOUCX?usp=sharing)


## 2. SVM — MNIST Dataset
The `svm-mnist.ipynb` is a Jupyter Notebook with my implementation of a LINEAR Support Vector Machine Model. I used the **sci-kit learn** library to easily implement the SVM model.

The algorithm performed at a **97.92%** accuracy.

![svm-performance](https://raw.githubusercontent.com/psrth/intro-to-machine-learning/main/imgs/svm-result.png)

You can find this project on a **Google Colab** notebook [here.](https://colab.research.google.com/drive/1C4NPNzLrBHv2VXo3STBdyJ9W-sCnOUCX?usp=sharing)

## 3. 2-Layered Neural Net — MNIST Dataset
The `neural_net-mnist.ipynb` is a Jupyter Notebook with my implementation of a 2-Hidden Layer Neural Network. I used the **PyTorch** library to easily implement the network. It goes from 784 > 128 > 64 > 10 nodes.

The algorithm performed at a **97.92%** accuracy.

![svm-performance](https://raw.githubusercontent.com/psrth/intro-to-machine-learning/main/imgs/nn-result.png)

You can find this project on a **Google Colab** notebook [here.](https://colab.research.google.com/drive/1C4NPNzLrBHv2VXo3STBdyJ9W-sCnOUCX?usp=sharing)