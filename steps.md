
```commandline
pip install cookiecutter
```

```commandline
cookiecutter https://github.com/drivendata/cookiecutter-data-science
```

```commandline
https://drivendata.github.io/cookiecutter-data-science/
```

```
add all git commands and push the file
```

```commandline
git checkout -b dev 
```

# To Untrack Files in Github

```commandline
git rm -r --cached 'Training_Batch_Files/*.csv' 
```

```commandline
git commit -m "stop tracking Training_Batch_Files/*.csv" 
```

```commandline
git rm -r --cached 'Prediction_Batch_files/*.csv' 
```

```commandline
git commit -m "stop tracking Prediction_Batch_files/*.csv"
```

# Dvc Setup

```commandline
pip install dvc
```

```commandline
dvc init 
```

```commandline
dvc add Training_Batch_Files/*.csv Prediction_Batch_files/*.csv

```
