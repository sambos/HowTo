## Python Virtual Environments


### using pipenv


installs new environment, looks for Pipfile if exists for reuse, creates a pipfile is does not exist
```sh
pip install pipenv
pipenv install 
```
Activate env
```
Pipenv shell (activates)
```

convert a Pipfile and Pipfile.lock into a requirements.txt file :
```
Pipenv lock -r > requirements.txt
```

install packages exactly as specified in Pipfile.lock using the sync command:

```
# --three -> use python 3
pipenv --three sync
pipenv lock --clear
```





### using virutalenv

Create venv:
```sh
python -m venv env
```

Activate:
```
.\env\Scripts\activate
```

Deactivate: 
```
deactivate
```

Installing packages from requirements
``` sh
Requirements.txt
setuptools
wheel
numpy
pandas
xlrd
matplotlib
jupyter
pytest

pip install -r requirements.txt

# capture packages
Pip freeze

pip install --upgrade pip setuptools wheel
pip install --upgrade setuptools

```

