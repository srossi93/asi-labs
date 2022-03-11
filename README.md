# Advanced Statistical Inference 

This course focuses on the principles of learning from data and quantification of uncertainty, by complementing and enriching the Introduction to Statistical Learning course. 
The presentation of the material follows a common thread based on the probabilistic data modeling approach, so that many classical algorithms, such as least squares and k-means, can be seen as special cases of inference problems for more general probabilistic models. Taking a probabilistic view also allows the course to derive inference algorithms for a class of nonparametric models that have close connections with neural networks and support vector machines. 
This advanced course is complemented by these lab sessions to guide students through the design and validation of the methods developed during the lectures.


### [Suggested] Google Colab
[Google Colab](https://colab.research.google.com/) is the suggested way to edit and execute the labs. Simply click on the icon to open the corresponding notebook in Colab. 

|  |   |  |
|:--|:--|:--|
| **Week 0** | Introduction to Python/Numpy  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/srossi93/asi-labs/blob/master/lab_week0-public/Tutorial_Python.ipynb)|
| **Week 1** | Bayesian linear regression    | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/srossi93/asi-labs/blob/master/lab_week1-public/Bayesian_Linear_Regression.ipynb)|
|            | Coin toss experiment          | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/srossi93/asi-labs/blob/master/lab_week1-public/Coin_Toss_Experiment.ipynb)|
| **Week 2** | Gaussian process regression   | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/srossi93/asi-labs/blob/master/lab_week2-public/Gaussian_Process_Regression.ipynb)|
| **Week 3** | Logistic regression with MCMC | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/srossi93/asi-labs/blob/master/lab_week3-public/Bayesian_Logistic_Regression_MCMC.ipynb)|
| **Week 4** | Variational inference         | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/srossi93/asi-labs/blob/master/lab_week4-public/Variational_Logistic_Regression.ipynb)|

### [Advanced] Local Jupyter

Note: choose this option only if you know what you are doing. 
You can clone the development environment using Conda (installation guide [here](https://docs.conda.io/en/latest/miniconda.html)), by running
```shell
> conda env create --file=environment.yml
```
Once the installation has completed, you can activate the new environment with 
```shell
> conda activate asi
```
Finally launch Jupyter Lab with 
```shell
> jupyter lab 
```
