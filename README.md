# Sound Classification for quality control in assembly processes

This Repository is a deep learning pipeline for classification of a special noise in an assembly process.
This Code is the base of our paper.

## Set up training data
Our whole dataset is available at Google.drive.
We labeled the data ourself and create 4325 data examples.
If you clone our repository please set up the paths according to the path in our Jupter Notebooks.

## Jypter Notebooks on [Google Colab](http://colab.research.google.com)

* Select 'Runtime' -> 'Change runtime time' -> 'Python 3' (and 'GPU') before running the notebook.
* Ignore the warning: 'This notebook was not authored by Google.' Check 'Reset all runtimes before running' and click 'Run anyway'

Train and check out our models at [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/adrian398/Sound_classification/blob/master/CNN_classification.ipynb)

or 

Check out our XGB, SVM, RF, GNB Benchmarking [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/adrian398/Sound_classification/blob/master/Benchmarking.ipynb)

or 

Check out our Visualizations and plots for the paper at [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/adrian398/Sound_classification/blob/master/Visualize_data.ipynb)

## Models
In the subfolder models you can access all our trained models and directly use them for your own predictions.
