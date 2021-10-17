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


git init


dvc init

dvc add data_given/winequality.csv

git add .

git commit -m "first commit"

oneliner update for readme

git add .&& git commit -m "update README.md"


git remote add origin https://github.com/sarikamohan08/simple_dvc.git

git branch -M main

git push origin main