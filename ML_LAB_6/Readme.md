# Problem Statement:   

Consider images from MNIST dataset (a handwritten digits database) where each image is of size
28x28. The dataset is divided into two sets – training set and test set. Training set consists on 60000
images whereas test set consists of 10000 images. The dataset can be easily downloaded from
several online websites like kaggle/tensorflow (inbuilt available)/http://yann.lecun.com/exdb/mnist/  
  
Actually the images of MNIST dataset are in R784.  
1. Apply PCA on training set of MNIST dataset to come to in R9 space. Let A is your transformation matrix (the columns of A are eigenvectors corresponding to nine largest eigenvalues). Use the transformation matrix A to bring test samples to R9 space and finally classify them using k-NN classifier for k = 3, and 5.  
2. In Task-1, replace PCA with LDA and repeat the experiment again.     
3. In Task-1, replace PCA with AUTO-ENCODER (784-P-Q-R-9) and repeat the experiment again.    
4. Compare the test accuracies in each of the above cases.  
You can think of a decoder network of structure : (9-P’-Q’-R’-784) in order to execute Task – 3.   
