
# Deep learning with Python: Personal workflow

This is my personal workflow with the ["Deep Learning with Python 2nd edition"](https://www.manning.com/books/deep-learning-with-python-second-edition?a_aid=keras&a_bid=76564dff) book. This notebooks can also be found at [fchollet repository](https://github.com/fchollet/deep-learning-with-python-notebooks) but here I try to tune every model that is presented.

## Environment installation

You can install on your computer all packages used in notebooks with:

```bash
foo@bar:~$ conda create --name NEWENV --file pkgs.txt
```

Because I am using Windows 10, tensorflow > **1.14** is not available with **conda**. If you are using MacOS or Linux you can install with conda.

```bash
foo@bar:~$ conda activate NEWENV
foo@bar:~$ conda install tensorflow
```

Otherwise you must install it through **pip**

```bash
foo@bar:~$ conda activate NEWENV
foo@bar:~$ pip install tensorflow
```

## Binary Classification: IMDB dataset

This is a dataset for binary sentiment classification, a set of 25,000 highly polar movie reviews for training, and 25,000 for testing.

The model presented in the book reachs a 88% test accuracy. Here, I will try to improve this score.

## Single-label multiclass Classification: Reuters newswires

A set of short newswires and their 46 topics. Each topic has at least 10 examples in the training set.

## Regression: Boston housing price dataset

Boston housing price datset has data points about the suburb in the mid-1970s, such as crime, local property tax rate, ... 404 training samples and 102 test samples.
