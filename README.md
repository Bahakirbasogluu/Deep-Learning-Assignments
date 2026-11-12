# Deep Learning Assignments

Assignments for AIN422 Deep Learning Laboratory, by Baha Kırbaşoğlu.

| File | Task | Methods | Dataset |
| --- | --- | --- | --- |
| `Assignment1/21992976-baha-kırbaşoğlu-hw1.ipynb` | Image classification on CIFAR-10, comparing classical classifiers with fully connected networks | k-NN and linear SVM (GridSearchCV) on standardized, PCA-reduced pixels with 10-fold cross-validation; fully connected Keras networks trained with Adam, SGD and Adadelta | [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) |
| `Assignment2/21992976_baha_kırbaşoğlu_hw2.ipynb` | Handwritten digit classification on MNIST | A loader for the raw IDX files, then four Keras CNN variants that differ in layer layout, learning rate, activation function, stride and pooling; evaluated with classification report and confusion matrix | [MNIST](http://yann.lecun.com/exdb/mnist/) |

Requirements: Python 3, Jupyter or Google Colab, numpy, matplotlib, opencv-python, scikit-learn, tensorflow (Keras).
