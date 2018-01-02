# MNIST - Deep Learning Using Caffe.

Steps:
1.  Run get.sh. This script downloads and unzips the mnist dataset.
2.  Caffe prefers lmdb files for large datasets. Hence need to run create.sh after running get.sh
    Change the EXAMPLE, and DATA paths to the working directory. Make sure to check the correct path for BUILD.
    Run create.sh
    We should now have train and test lmdb files in the working directory.
3.  Make sure the paths in solver and and train_test prototxt files are updated.
4.  Run train.py

We can also try changing the solver functions, number of layers, kernels etc to dwelve deep.
