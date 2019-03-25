# Keras-Regression-Classification

## Aim of this Repo:

Demonstration of how to use the Keras library in Deep Neural Networks to solve all common supervised and unsupervised problems including Regression as well as Classification Problems, with various inputs and outputs. The idea is to cover all the likely input and output scenarios and thereby deal with with all the common supervised and unsupervised problems.  The goal is that experienced developers who are investing effort in studying machine learning can find all the examples they need, but would be required to 'fix bugs' or solve problems and thereby learn machine learning by hands-on coding.  The reason why there should be issues to fix is that it is far too easy to clone a repo and run the notebooks and learn absolutely nothing.  So the idea is that a software engineer would fork the repo, and instead of submitting pull requests that contain solutions, they might submit pull requests containing additional problems. Any pull requests containing solutions will be rejected, though they can of course push solutions to their own fork.

Inside the Datasets folder, you will find requisite datsets in .csv format:

• hourly_wages_data

• diabetes_data

The code for demonstration of Keras usage is in .ipynb format, for example, in the file DL_Keras_Regression-&-Classification.ipynb for Regression and Classification. Additional notebooks are added as required to cover all the common input and output scenarios of supervised and unsupervised learning.

## Regression

Regression predictive modeling is the task of approximating a mapping function (f) from input variables (X) to a continuous output variable (y).

A continuous output variable is a real-value, such as an integer or floating point value. These are often quantities, such as amounts and sizes.

For example, a house may be predicted to sell for a specific dollar value, perhaps in the range of $100,000 to $200,000.

• A regression problem requires the prediction of a quantity.  
• A regression can have real valued or discrete input variables.  
• A problem with multiple input variables is often called a multivariate regression problem.  
• A regression problem where input variables are ordered by time is called a time series forecasting problem.

## Classification

Classification predictive modeling is the task of approximating a mapping function (f) from input variables (X) to discrete output variables (y).

The output variables are often called labels or categories. The mapping function predicts the class or category for a given observation.

For example, an email of text can be classified as belonging to one of two classes: “spam“ and “not spam“.

• A classification problem requires that examples be classified into one of two or more classes.  
• A classification can have real-valued or discrete input variables.  
• A problem with two classes is often called a two-class or binary classification problem.  
• A problem with more than two classes is often called a multi-class classification problem.  
• A problem where an example is assigned multiple classes is called a multi-label classification problem.

## Classification Vs Regression

Classification predictive modeling problems are different from regression predictive modeling problems.

Classification is the task of predicting a discrete class label.
Regression is the task of predicting a continuous quantity.
There is some overlap between the algorithms for classification and regression; for example:

A classification algorithm may predict a continuous value, but the continuous value is in the form of a probability for a class label.
A regression algorithm may predict a discrete value, but the discrete value in the form of an integer quantity.

## But what IS Keras?

Keras is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano. It was developed with a focus on enabling fast experimentation. Being able to go from idea to result with the least possible delay is key to doing good research.

Use Keras if you need a deep learning library that:

Allows for easy and fast prototyping (through user friendliness, modularity, and extensibility).
Supports both convolutional networks and recurrent networks, as well as combinations of the two.
Runs seamlessly on CPU and GPU.

### Very importantly, Keras has been comprehendably documented at https://keras.io/ 

Do check it out!
