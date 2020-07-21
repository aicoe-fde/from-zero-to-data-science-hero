# fraud-notebooks

These notebooks accompany our workshop _From Statistics to Serverless:  Intelligent Applications on OpenShift 4_.  Our slide deck from delivering this workshop at Red Hat Summit is available [as a PDF](slides.pdf) or [as a movie](slides.m4v).

In order to build and run a model service, you'll need an OpenShift cluster, but you can experiment with the notebooks on your own time.  Here's how:

## The easy way

Use [binder](https://mybinder.org/v2/gh/willb/fraud-notebooks/develop).  (We don't recommend this if you'll be running the tutorial over conference wifi, but it requires almost no setup and can run from a computer that only has a browser.)

## The flexible way

If you want to experiment with the data generator, you'll want to use your own computer.

### Install the prerequisites

1. Make sure you have Python 3.7 installed, installing it if necessary
    - If you have a favorite package manager, use that 
    - if not, [python.org](https://www.python.org/downloads/) has binaries for many platforms
2. Make sure you have `git` installed, installing it if necessary
    - If you have a favorite package manager, use that
    - if not, [git-scm.com](https://git-scm.com/downloads) has binaries for many platforms (you won't need a GUI)
3. Install [pipenv](https://docs.pipenv.org/en/latest/)
    - on a Mac, the easiest way is probably `brew install pipenv`
    - on a Fedora Linux machine, the easiest way is probably `dnf install pipenv`
    - on Windows, if you have Python installed already, the easiest way is probably [to use `pip`](https://docs.pipenv.org/en/latest/install/#pragmatic-installation-of-pipenv)  
    
### Install the notebooks and dependencies

1.  Clone this repository:  `git clone https://github.com/willb/fraud-notebooks/`
    - tip:  if you don't have `git` installed, you can also [download an archive of this repository](https://github.com/willb/fraud-notebooks/archive/develop.zip)
2.  Change to this repository's directory:  `cd fraud-notebooks`
3.  Install the dependencies:  `pipenv install`
4.  Run the notebooks:  `pipenv run jupyter notebook`

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/willb/fraud-notebooks/develop)

