# Generative Adverserial Networks for MNIST

This is an example of generating adversarial examples to exploit the deep MNIST Convolution network. It is inspired from [Intriguing Properties of Neural Networks](http://arxiv.org/abs/1312.6199), [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572)
and [Breaking Convnets](http://karpathy.github.io/2015/03/30/breaking-convnets/).  

## Setup Instructions

1. Clone the repository. 
```
git clone https://github.com/divyam3897/adversarial-examples.git
```
2. Make sure tha you have Jupyter Notebook installed. You can install Anaconda (which installs Python, Jupyter Notebook, and a bunch of other useful computing libraries) or use pip.

- To install [Anaconda](https://www.continuum.io/downloads).

- If you want to install using pip, update pip with the following code (Replace pip with pip3 if using Python 3). 

On Linux/Mac OS:
```
pip install -r requirements.txt
```

You should be able to run the following. 
```
pip install jupyter
```

3. Run the following command to open the jupyter notebook in the browser.
```
jupyter notebook
```

For more resources on Jupyter Notebooks, check out the following:
* [Installation Documentation](http://jupyter.readthedocs.io/en/latest/install.html)
* [Trying Jupyter](https://try.jupyter.org/) just in your browser
* [Jupyter Docs](https://jupyter.readthedocs.io/en/latest/index.html)

## Result

The image below shows 10 samples of 2 on the left, perturbation in the middle and the adversarial examples on the right
![Adversarial examples](https://github.com/divyam3897/adversarial-examples/blob/master/test.png)
