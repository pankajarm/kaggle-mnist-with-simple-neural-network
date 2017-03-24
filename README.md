# kaggle-mnist-with-simple-neural-network

Result = 97.2799

Submission for Kaggle mnist Challenge, with Simple Neural Network based on pure python, scipy and numpy, no deep learning packages (Tensor Flow, Theano, Torch) used..

### Install
I am using [Conda](https://www.continuum.io/anaconda-overview) to install TensorFlow. You might already have a TensorFlow environment, but please check below to make sure you have all the necessary packages. If you have never used Conda environments before, please go through my other tutorial [What is Anaconda and Why should I bother about it?](http://pankajmathur.com/what-is-anaconda-and-why-should-i-bother-about-it/)

Assuming you have conda install on your machine, plesae run the following commands:

### OS X or Linux
Run the following commands to setup your environment:

```
conda create -n kaggle-mnist-snn python=3
source activate kaggle-mnist-snn
conda install matplotlib scipy jupyter notebook
```

### Windows
And installing on Windows. In your console or Anaconda shell:

```
conda create -n kaggle-mnist-snn python=3
activate kaggle-mnist-snn
conda install matplotlib scipy jupyter notebook
```
After creating conda environment, clone or download zip (and then extract) this repository on your local machine, cd to that directory in your terminal or shell and then run following command

```
jupyter notebook first_neural_network.ipynb
```
