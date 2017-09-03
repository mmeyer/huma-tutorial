Installation instructions for Huma tutorial
===========================================


To install the required software on your machine with your preferred OS you and follow these instructions here: [https://machinelearningmastery.com/setup-python-environment-machine-learning-deep-learning-anaconda/](https://machinelearningmastery.com/setup-python-environment-machine-learning-deep-learning-anaconda/)

If you prefer to use a VM to run the tutorial you go to this [Github repository](https://github.com/mmeyer/deep-learning-vm.git) and follow the instructions in the README.md.

With that instructions you will install the following required software:
- python 3
- scipy
- numpy
- pandas
- sklearn
- theano
- tensorflow
- keras
- jupyter

What it does not yet install is the following software, which you can install with the following commands

`conda install -c graphviz`

`pip install matplotlib`

`pip install graphviz`

`pip install pydot`


After you setup all software you need to checkout my gitHub repository, with all the files for the tutorial. The command would be as following:

`git clone https://github.com/mmeyer/huma-tutorial`

to check if all the required software is installed correctly in your environment, you call in your terminal/shell

`python software_version_check.py`

in the root folder of this Github repository that just you just checkout.

You should get the following message back if you installed all required software versions correctly, only the versions shown might change.

````
scipy: 0.19.1
numpy: 1.13.1
matplotlib: 2.0.2
pandas: 0.20.3
sklearn: 0.18.2
theano: 0.9.0
tensorflow: 1.2.1
Using TensorFlow backend.
keras: 2.0.6
````

If that is the case you start with the following command

`jupyter notebook`

in the root folder of the Huma tutorial the juypter process.

The browser is automatically opened with the following url [http://localhost:8888/tree](http://localhost:8888/tree) to load the jupyter environment, where you can interactively run through the tutorial. You will see in the browser the jupyter file listing and by just double clicking the `huma_tutorial.ipynb` juypter notebook file the tutorial opens and you can interactively learn about how the AI in Huma works.
