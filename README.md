# python-tools

This repo contains the requirments to boostrap our python-tools virtual environment.

## Applications

* CSVKit
* Leg.it
* bpython
* mycli
* youtube-dl
* httpie
* watchdog
* beancout
* asciinema
* percol

## Languages
* coconut

## Libs

* requests
* GitPython
* xlrd
* SQLAlchemy
* paramiko
* flask
* jmespath

# Requirements

You should have installed:

  * python 3.6

    ```bash
    $> sudo add-apt-repository ppa:jonathonf/python-3.6
    $> sudo apt-get update
    $> sudo apt-get install python3.6
    ```

  * [virtualenv.py](https://virtualenv.pypa.io/en/stable/installation/)

# Installation

After clonning this repo you need to create the environment with:

```bash
$> cd to/this/repo/dir
$> mkdir ~/virtualenvs
$> virtualenv.py --python=python3 ~/virtualenvs/tools
$> source ~/virtualenvs/tools/bin/activate
$> pip install -r requirements.txt
```

# Usage

Each time you want to use the tools you need to activate the environment.

```bash
$> source ~/virtualenvs/tools/bin/activate
```
