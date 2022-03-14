# Implement the following variants of regression problems:  
  

  
# Regarding dataset used :  

Consider images from MNIST dataset (a handwritten digits database) where each image is of size
28x28. The dataset is divided into two sets – training set and test set. Training set consists on 60000
images whereas test set consists of 10000 images. The dataset can be easily downloaded from
several online websites like kaggle/tensorflow (inbuilt available)/http://yann.lecun.com/exdb/mnist/  
  
Actually the images of MNIST dataset are in R784.  
1. Apply PCA on training set of MNIST dataset to come to in RM space where M = 5, 10, 25, 64, 100, 200, 784.  
2. For each M, show the principal components (in image format).    
3. Compute the original feature space for each of the values of M. Also find the Mean Square Error (MSE) for each of the cases.    
4. Construct an AUTO-ENCODER (784-P-Q-R-M) ; P, Q, R, and M are number of neurons in your neural network. Repeat the Task – 1 and the Task – 3 for this AUTO-ENCODER and compare its performance in terms of MSE with PCA.    
You can think of a decoder network of structure : (M-P’-Q’-R’-784) in order to execute Task – 4.  
