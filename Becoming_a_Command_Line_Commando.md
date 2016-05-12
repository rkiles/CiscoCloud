# Becoming a Command Line Commando

## Installing the Openstack Command Line tools

The Openstack Command Line tools are essentially a Python library.  If you are not familiar with Python, it is a modern interpreted language that has a simple syntax and is easy to learn while also being full-featured and extremely powerful.  

So, the first step in installing the Openstack Command Line tools is to first get Python installed.  One important thing to understand about Python is that there are currently two distinct versions of Python; Python 2 and Python 3.  The Openstack Openstack Command Line tools are currently only work with the older Python 2 and so that is what we will install.

Below are some great tutorials if you need help installing Python 2 on Windows, Mac, or Linux:

[Installing Python on Windows](http://docs.python-guide.org/en/latest/starting/install/win/)

[Installing Python on Linux](http://docs.python-guide.org/en/latest/starting/install/linux/)

[Installing Python on Mac OS X](http://docs.python-guide.org/en/latest/starting/install/osx/)

(If you run into any issues, feel free to open an issue on this Github repository for help)

## Becoming Pythonic

Once you have Python installed pat yourself on the back and bask in the knowledge that your assimiliation into the Python collective has begun!

Now, lets test out your Python and make sure it works.  Open you command line and type:

```
$ python --version
```

You should get back something like: `Python 2.7.11`

## Using `pip` to install the Openstack Command Line tools

Pip is the Python package manager and will manage all the dependencies that any library requires.  Its like apt-get for Python.

We first need to make sure it is installed though.  It usually comes built in to most Python installs these days.

```
pip list
```

Output you should see:

```
Flask (0.10.1)
itsdangerous (0.24)
Jinja2 (2.8)
MarkupSafe (0.23)
pip (8.1.1)
setuptools (18.2)
virtualenv (15.0.1)
Werkzeug (0.11.5)
```

Note: Your install may show different libraries.



