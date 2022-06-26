# demo-flask for borrow system

## Pre-request
- this project use python3.8, please check whether you have python3.8
    - test with `ls /usr/bin/python3.8`
    - if not, install it with following command
        - `sudo add-apt-repository ppa:deadsnakes/ppa`
        - `sudo apt install python3.8`
- install pipenv
    - `pip install pipenv`
- clone this repo
    - `git clone https://github.com/efficacy38/demo-flask.git`
- change directory 
    - `cd demo-flask`
- setup virtual environment
    - `pipenv install`

## environment variable
- `.env` would be autoloaded by pipenv script
    - `FLASK_APP`: flask application name

## how to start
- run development mode with pipenv script
    - `pipenv run dev`

