
# Low Code: Environment

This repository is in-progress.

## Test dataset

Example 2 tier

```
category,count
code,60
click,12
```

```
code_category,count
python,20
r,30
javascript,10
```


## Development

A clean virtual environment with Python 3.9.10

```bash
pyenv virtualenv 3.9.10 jupyter-3-9-10
pyenv activate jupyter-3-9-10
pip install jupyterlab pandas keplergl geopandas mitosheet
```
