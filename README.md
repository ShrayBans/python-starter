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

- Run `poetry show -v` to find out the virutalenv location.
- Take the outputted path: `/Users/bansalshray/Library/Caches/pypoetry/virtualenvs/python-starter-Ak27cIVH-py3.7`
- Create `.vscode` folder and add a `settings.json` which will represent workspace only settings and add settings:
```
{
  "python.pythonPath": "/Users/bansalshray/Library/Caches/pypoetry/virtualenvs/python-starter-Ak27cIVH-py3.7",
  "python.linting.pylintEnabled": false,
  "python.linting.enabled": true,
  "python.linting.flake8Args": ["--max-line-length=500"],
  "python.linting.flake8Enabled": true,
  "python.formatting.provider": "black",
  "python.formatting.blackArgs": ["--line-length=140"]
}
```

### Using this repo as a template
Go to the directory you want this project to be into
```
cp -r /Users/bansalshray/Desktop/Projects/python-starter/. .
````
- Change the names of `python-starter`
- Remove `.git` and reinit the git repo