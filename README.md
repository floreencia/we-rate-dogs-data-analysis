# we-rate-dogs-data-analysis
Analysing the WeRateDogs Twitter account. Practising data wrangling and analysis. 

## Installation

### Install Python 3 and packages using conda package manager
    
    $ conda install pandas numpy python=3.6 matplotlib seaborn

### Install nbextensions and wordcloud package
 
    $ conda install -c conda-forge jupyter_contrib_nbextensions wordcloud
    
 ### Install further packages using pip package manager
 
    $ pip install requests tweepy jsonschema
    
### Install Jupyter Notebook

You can find the installation documentation for the
[Jupyter platform, on ReadTheDocs](https://jupyter.readthedocs.io/en/latest/install.html).
The documentation for advanced usage of Jupyter notebook can be found
[here](https://jupyter-notebook.readthedocs.io/en/latest/).

For a local installation, make sure you have
[pip installed](https://pip.readthedocs.io/en/stable/installing/) and run:

    $ pip install notebook

## Usage - Running Jupyter notebook

### Running in a local installation

Launch with:

    $ jupyter notebook
    
### Running in a remote installation

You need some configuration before starting Jupyter notebook remotely. See [Running a notebook server](http://jupyter-notebook.readthedocs.io/en/stable/public_server.html).

## Twitter API

Apply for a Twitter API account and provide your own login information, before running the API request.