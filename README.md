# Head-Pose-Estimation-using-Deep-Learning

Problem Statement
We are going to try to estimate the head pose of a person using Convolutional Neural Network. To predict Head Pose we need to predict two labels i.e Tilt - Vertical angle of the head , Pan - Horizontal angle of the head. For this purpose we will try to use two different types of Convolutional Neural Networks.

Data
The original data is from Head Pose Image Database (http://www-prima.inrialpes.fr/perso/Gourier/Faces/HPDatabase.html) published with N. Gourier, D. Hall, J. L. Crowley, “Estimating Face Orientation from Robust Detection of Salient Facial Features”, Proceedings of ICPR International Workshop on Visual Observation of Deictic Gestures 2004.
Licence agreement: The dataset can only be used for the purpose of this assignment. Sharing or distributing this data or using this data for any other commercial or non-commercial purposes is prohibited.

Task
We need to predict two labels (hence multilabel classification) which are tilt and pan.

Approaches
First approach will be Branching Convolutional Network (BCNN)
Second approach would be sequential CNN.

Major Steps
We are going to Label binarize our two labels (tilt and pan) to 22 columns(classes) and augment the data

Results
BCCN gave an accuracy of 0.8108 on tilt (validation set) and accuracy of 0.1935 on pan(validation set). 
Sequential CNN gave us an overall acuracy of 0.7656

Submissions
Requirement file for project is available as COSC2779_Assignment1.pdf
our final trained model is saved as HeadPoseCNNClassifier.h5
predictions are saved in s3796258.csv
Report is available as Deep Learning report
