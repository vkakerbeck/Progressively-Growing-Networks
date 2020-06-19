# Progressively Growing Neural Networks
This is code to several experiments on different dataset (MNIST, CIFAR-10 and CIFAR-100) on how to grow networks during training 
and to learn new image categories. It is the code underlying my master thesis which is also provided here for a better understanding and 
some additional context. The file TestAccuracies.csv contains all my results and is used in the analysis parts of the code. You can of course replicate this data on your own with the code provided but since this will take several days I provide my results already in TestAccuracies.csv. The full PDF version of my master thesis can be found in the main folder.

## Blog Posts
Progressive Learning and Network Growing in TensorFlow:
https://towardsdatascience.com/progressive-learning-and-network-growing-in-tensorflow-e41414f304d2

How to Improve Your Network Performance by Using Curriculum Learning:
https://towardsdatascience.com/how-to-improve-your-network-performance-by-using-curriculum-learning-3471705efab4

## Cite this Work
Kakerbeck, V. (2018). Progressively Growing Neural Networks for Scene
Graph Generation from Images (Master thesis, University of Osnabrück,
Germany). https://doi.org/10.13140/RG.2.2.26794.44488.

Blogposts:
Clay, V. (2018, December 21). Progressive Learning and Network Growing in
TensorFlow [Blog post]. Retrieved from
https://towardsdatascience.com/progressive-learning-and-network-growing-in-tensorflow-e41414f304d2

Clay, V. (2019, January 7). How to Improve Your Network Performance by
Using Curriculum Learning [Blog post]. Retrieved from
https://towardsdatascience.com/how-to-improve-your-network-performance-by-using-curriculum-learning-3471705efab4


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
