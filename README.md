# Password storage demo

As part of my Software Security classes, I want to do a live demo of different
password storage algorithms:

* Hashing: MD5, SHA1, SHA256
* Key Derivation Functions: BCrypt

## Setup

You need Python for this. This was tested with Python 2.7.12 on a Fedora machine
with a virtual environment
(<https://virtualenvwrapper.readthedocs.io/en/latest/>), which I encourage to
use for setup and running of the code. Run `pip install -r requirements.txt`
inside your virtual environment and all dependencies will be installed.

## Run the demo

Now, run the demo using the following command:

```shell
jupyter notebook
```

A web server will start locally, and browser window will open, showing a list of
Notebooks. Click on __algorithms.ipynb__ and you will be at the demo.
