# Udacity Machine Learning Engineer Nanodegree
## Capstone Project: Kaggle Leaf Classification
> Author: Ke Zhang
>
> Submission Date: 2017-05-23 (Revision 1)

### Capstone Proposal:

* Review Link: https://review.udacity.com/#!/reviews/484187

### Dataset:

The leaf classification dataset can be obtained on the Kaggle competition page: 
* https://www.kaggle.com/c/leaf-classification/data
* all of the dataset files have to be extracted into the ./data directory

#### File descriptions

Dataset:
* data/train.csv - the training set
* data/test.csv - the test set
* data/sample_submission.csv - a sample submission file in the correct format
* data/images/* - the image files (each image is named with its corresponding id)

Project Files:
* p6_kaggle_leaf_code.ipynb - project documentation and execution code
* p6_kaggle_leaf_code.html - html version of project.ipynb
* submission.csv - the final submittion to Kaggle including the predictions of the testing set
* p6_kaggle_leaf_model.html - graph of the tensorflow neural network model
* model/* - tf graph saved to disk 

#### Data fields

* id - an anonymous id unique to an image
* margin_1, margin_2, margin_3, ..., margin_64 - each of the 64 attribute vectors for the margin feature
* shape_1, shape_2, shape_3, ..., shape_64 - each of the 64 attribute vectors for the shape feature
* texture_1, texture_2, texture_3, ..., texture_64 - each of the 64 attribute vectors for the texture feature

#### Development Environment

* Python 3.5.3
* scikit-learn 0.18.1
* scikit-image 0.12.3
* tensorflow 1.1.0
* opencv 3.2.0

### References:

1. [Kaggle Leaf Classification Competition](https://www.kaggle.com/c/leaf-classification): The subject of this proposal is derived from one of the most popular Kaggle playground competitions with more than 1500 participants.
2. [The MNIST Database of Handwritten Digits by Yann LeCun et al](http://yann.lecun.com/exdb/mnist/)
3. [Kaggle Leaf Competition Winner Interview](http://blog.kaggle.com/2017/03/24/leaf-classification-competition-1st-place-winners-interview-ivan-sosnovik/)
4. [Log Loss Definition](https://www.kaggle.com/wiki/LogLoss)
5. [Udacity Deep Learning](https://www.udacity.com/course/deep-learning--ud730)

Additional references listed on the last page in the report.pdf.