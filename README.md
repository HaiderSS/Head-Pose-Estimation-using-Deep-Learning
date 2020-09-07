# Head-Pose-Estimation-using-Deep-Learning
We are going to try to estimate the head pose of a person using Convolutional Neural Network.For this purpose we will try to use two different types of Convolutional Neural Networks.

We need to predict two labels (hence multilabel classification) which are tilt and pan

First approach will be Branching Convolutional Network (BCNN)
Second approach would be sequential CNN.

We are going to Label binarize our two labels (tilt and pan) to 22 columns(classes).

our final trained model is saved as HeadPoseCNNClassifier.h5

predictions are saved in s3796258.csv
