# Progressively Growing Neural Networks
This is code to several experiments on different dataset (MNIST, CIFAR-10 and CIFAR-100) on how to grow networks during training 
and to learn new image categories. It is the code underlying my master thesis which is also provided here for a better understanding and 
some additional context. The file TestAccuracies.csv contains all my results and is used in the analysis parts of the code. You can of course replicate this data on your own with the code provided but since this will take several days I provide my results already.

## Dependencies

* jupyter notebook
* tensorflow
* numpy
* pandas
* pickle

For plotting and data analysis:

* matplotlib
* seaborn
* augmentation module from https://github.com/aleju/imgaug for CIFAR-100 experiments
* ptitprince for some of the plots
* statsmodels & scipy for significance tests and linear regression
