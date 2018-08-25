# Django-Deployment

## How to install Django on Windows

This document will guide you through installing Python 3.5 and Django on Windows. It also provides instructions for installing virtualenv and virtualenvwrapper, which make it easier to work on Python projects. This is meant as a beginner’s guide for users working on Django projects and does not reflect how Django should be installed when developing patches for Django itself


## About pip
pip is a package manage for Python. It makes installing and uninstalling Python packages (such as Django!) very easy. For the rest of the installation, we’ll use pip to install Python packages from the command line.

To install pip on your machine, go to https://pip.pypa.io/en/latest/installing/, and follow the Installing with get-pip.py instructions.

## Install virtualenv and virtualenvwrapper

```
pip install virtualenvwrapper-win
```
## Then create a virtual environment for your project:
```
mkvirtualenv myproject
```
## The virtual environment will be activated automatically and you’ll see “(myproject)” next to the command prompt to designate that. If you start a new command prompt, you’ll need to activate the environment again using:

```
workon myproject
```

## Install Django
Django can be installed easily using pip within your virtual environment.

```
pip install django
```
