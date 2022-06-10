
# my Machine Learning for Time Series Forecasting with Python
6/9/2022

book: Machine Learning for Time Series Forecasting with Python  
author: Francesca Lazzeri, PhD.  
forked from FrancescaLazzeri https://github.com/FrancescaLazzeri/Machine-Learning-for-Time-Series-Forecasting  

##### myBits
- my work through code is marked with `$my`. 
- my worked-through files are marked with `my#_FileName`


# Machine Learning for Time Series Forecasting with Python

To configure your environment you will need Anaconda, the Python Distribution.

The instructions for installing Anaconda can be found [here](https://docs.anaconda.com/anaconda/install/)

Once Anaconda is installed you should have `conda` executable in your environment path.

Anaconda provides a concept called environments which allow us to have different dependencies based on what we're working on. The documentation is available [here](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)

We would like to use different conda environment for running jobs on our machines, but when we submit jobs to Azure Machine Learning we will use a different environment. To provide easy access to these environments in jupter notebooks or jupyter lab we can use `nb_conda` into Anaconda's base environment.

```{bash}
conda install -n base nb_conda
```
