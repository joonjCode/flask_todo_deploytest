# flask_todo_deploytest

Need flask
will run app.py not app2.py

recommended to use virtualenv

## Install and Create venv
Install
windows : `pip install virtualenv`
mac : `pip3 install virtualenv`  

Create
mac : `python3 -m venv ./venv`
windows : `python -m venv ./venv`

## activate venv
mac : source venv/bin/activate
windows : venv\Scripts\activate.ps1

## install requirements.txt 
This will install packages inside the text file


`pip install -r requirements.txt`  

Check for installed packages
`pip freeze`

## Run file
`python app.py` (recommended)
or
`flask run` 
with error `set FLASK_APP=<name of your python file>`




