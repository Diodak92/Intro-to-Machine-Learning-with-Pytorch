# Intro to Machine Learning with Pytorch

## Prerequirements

**To run scripts from this repo on your local machine**

1. Install [Anaconda](https://www.anaconda.com)
2. Verify that conda has been properly installed by typing the command: ```conda -V```
In response, you should get a similar output: ```conda 22.11.1```
3. Create an enviroment from yaml file by entering the command:
```conda env create -f req_packages.yml```
4. Verify that the environment has been created: ```conda env list```
5. Activate enviroment: ```conda activate image_classifier``` 
6. Set the path to download the files: ```cd my/own/path``` 
7. Download repo: ```git clone https://github.com/Diodak92/Intro-to-Machine-Learning-with-Pytorch.git```
8. Open project directory cd: ```cd my/own/path/Intro-to-Machine-Learning-with-Pytorch```
9. Open Jupyter Notebook by entering the command: ```jupyter notebook```
10. Open the selected project file with the extension ```.ipynb``` 

### Project 2: [CIFAR-10 Image Clasifier](https://github.com/Diodak92/Intro-to-Machine-Learning-with-Pytorch/blob/main/CIFAR-10_Image_Classifier/CIFAR-10_Image_Classifier.ipynb) 🎑

The goal of this project was to build a simple image classifier using the popular deep learning package: [PyTorch](https://pytorch.org). The classifier is designed to recognize 10 categories of images from the [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html). The images have a small resolution of 32x32 pixels, so it is possible to train the neural network on the computer's CPU, but it is preferable to train on the GPU if such an option is available. It took more than 16 min to train for 30 epochs on a computer with an i5 processor.
