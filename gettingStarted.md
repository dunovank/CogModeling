# Getting started

### Anaconda & Jupyter
* includes most scientific python packages, [jupyter](http://jupyter.org/), etc.
* Install **Python 3.6 version** for:
 * [OSX](https://www.anaconda.com/download/#macos)
 * [Linux](https://www.anaconda.com/download/#linux)
 * [Windows](https://www.anaconda.com/download/#windows)
* After installing Anaconda, play around with `jupyter notebook`
```sh
# open up a terminal and execute the command below
jupyter notebook
```
* Useful walkthrough of jupyter notebook features ([here](https://medium.com/codingthesmartway-com-blog/getting-started-with-jupyter-notebook-for-python-4e7082bd5d46))

### Installing HDDM for Python 3.6

* First, try the following:
```sh
pip install --upgrade pymc
pip install --upgrade kabuki hddm
# reinstall numpy version 1.11 (latest version incompatible with hddm)
pip install numpy==1.11.3
```

* If you run into errors with the first approach, you can try:
```sh
conda install -c pymc hddm
```
* If neither works, we can sort it out together during our first meeting

### Getting familiar w/ HDDM:
We'll go through a lot of this together so don't feel obligated to go through all of this before our first meeting. Just including these links in case anyone wants to do a little background reading in the mean time.
* Official methods paper ([here](https://www.frontiersin.org/articles/10.3389/fninf.2013.00014/full))
* Introductory demo ([here](http://ski.clps.brown.edu/hddm_docs/tutorial_python.html))
* Additional How-to ([here](http://ski.clps.brown.edu/hddm_docs/howto.html))
