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

  * Dependencies

  ```bash
    $> sudo apt-get install build-essential checkinstall
    $> sudo apt-get install libreadline-gplv2-dev libncursesw5-dev libssl-dev libsqlite3-dev tk-dev libgdbm-dev libc6-dev libbz2-dev
    $> sudo apt-get install libsasl2-dev libldap2-dev
  ```

  * python 3.6

    ```bash
    $> sudo add-apt-repository ppa:jonathonf/python-3.6
    $> sudo apt-get update
    $> sudo apt-get install python3.6 python3.6-dev
    ```

  * [virtualenv.py](https://virtualenv.pypa.io/en/stable/installation/)

# Installation

After clonning this repo you need to create the environment with:

```bash
$> cd to/this/repo/dir
$> mkdir ~/virtualenvs
$> virtualenv.py --python=python3.6 ~/virtualenvs/tools
$> source ~/virtualenvs/tools/bin/activate
$> pip install -r requirements.txt
```

# Usage

Each time you want to use the tools you need to activate the environment.

```bash
$> source ~/virtualenvs/tools/bin/activate
```
