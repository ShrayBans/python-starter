# Shray's Python Starter

- Sets up the app structure as I want.
- Sets up the basic linting / formatter settings
- Instructions on Poetry /


## Setup
Run this to and then adjust your Python Interpreter to match the created virtualenv.
```
poetry install
```
Run the application (entrypoint is main.py) by running `./run_app.sh`

### IDE (VSCode)
In order to set up your IDE to have all the bells and whistles, you need to attach the virutalenv created by poetry to the IDE.

- From your terminal, run `poetry shell`. Then run `code .`
- You should be able to select the Python Intepreter now and it should have everything you need.

### Using this repo as a template
Go to the directory you want this project to be into
```
cp -r /Users/bansalshray/Desktop/Projects/python-starter/. .
````
- Change the names of `python-starter`
- Remove `.git` and reinit the git repo