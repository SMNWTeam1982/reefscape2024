# reefscape2024
Reefscape FRC Competition Team1982 project code

# Dependency Management
This project is using pipenv to manage dependencies, to install pipenv, use
```
pip install --user pipenv
```
This will install pipenv globally, which can be used with 
```
pipenv install <package>
```
To run commands in the virtual environment, use:
```
pipenv run python3 <command>
```
For example, to run the `robot.py` file, use:
```
pipenv run python3 robot.py
```
To download the RoboRIO precompiled binaries, use:
```
pipenv run sync
```

#### Note:
Please do not edit `Pipfile` or `Pipfile.lock`, as these files are managed by pipenv and can break otherwise.
