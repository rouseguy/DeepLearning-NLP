# Installation

## Pre-requisites
* Laptop running Linux / OSX / Windows operating system
* Minimum 4GB of RAM
* Laptop charger

## Recommended Installation
We will be using Python 2.7 version for the exercise. Users should install the Anaconda distribution from Continuum - [https://www.continuum.io/downloads](https://www.continuum.io/downloads).

Please note that installing Anaconda is the **recommended** option for the workshop.

## Post Anaconda Installation

**`keras`**

Please install `keras` using the following command

    $ pip install keras

**`tensorflow`**

Please install `tensorflow` using the instructions given [here](https://www.tensorflow.org/versions/r0.9/get_started/os_setup.html)

Please note that installing `tensorflow` on Windows is not straight forward. Attendees running Windows will be using `theano` as the back-end for `keras`. `theano` comes with Anaconda.
 
**`gensim`**

Please install `gesim` using the following command

    $ pip install gensim



## Content for the workshop

All tutorial content can be obtained from this repository either with `git`, or by downloading the repository content as a zip file. If you use git, you can clone this repostory:

```git clone https://github.com/rouseguy/europython2016_dl-nlp.git```

or, download and unzip the zipfile.

## Check installation

To test your installation, change to the tutorial directory, and run:

    $ python check_env.py

If the required packages are present, you will see the message:

    $ OK.  All required items installed.

If you see message to install particular package(s), please install them using the command:
    
    $ conda install <package name>
or
    
    $ pip install <package name>
    


