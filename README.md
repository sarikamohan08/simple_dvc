create env

```bash
conda create -n mlops_wine python=3.7 -y
```

activate env
```bash
conda activate mlops_wine
```

create requirements.txt file

install the requirements
```bash
pip install -r requirements.txt
```

download the data 

https://www.kaggle.com/rajyellow46/wine-quality

```bash
git init 

```
```bash
dvc init
```
```bash
dvc add data_given/winequality.csv
```
``` bash
git add .
```
```bash
git commit -m "first commit"
```

oneliner update for readme
```bash
git add .&& git commit -m "update README.md"
```
```bash
git remote add origin https://github.com/sarikamohan08/simple_dvc.git

git branch -M main

git push origin main
```

tox command
```bash
tox
```

for rebuilding
```bash
tox -r
```

pytest command
```bash
pytest-v
```

setup commands 
```bash
pip install -e .
```

build your own package
```bash
python setup.py sdist bdist_wheel
```

