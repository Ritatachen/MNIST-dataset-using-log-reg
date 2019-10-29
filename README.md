# MNIST-dataset-using-log-reg
logistic regression for digit classification


You have been given data (in data_digits_8_vs_9_noisy) corresponding to images of hand-
written digits (8 and 9 in particular).

this data has been split into various training,and testing sets; 
each set is given in CSV form, and is divided into inputs (x) and outputs (y).
Each row of the input data consists of pixel data from a (28 * 28) image with gray-scale values
between 0 (black) and 1 (white); this pixel data is thus represented as a single feature-vector of
length 282 = 784 such values. The output data is a binary label, with 0 representing an 8, and 1
representing a 9.


I will fit logistic regression models to the training data, using sklearn's implementation of the model, with the liblinear solver.

I will explore max_iter and values of the inverse penalty strength C. 
Analyze some of the mistakes that your best model makes.
Analyze all of the nal weights produced by your classifier.
