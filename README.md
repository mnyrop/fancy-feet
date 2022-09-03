# fancy-feet

### Requirements

- [Pyenv](https://github.com/pyenv/pyenv#installation)
- Git

### Run Jupyter

1. Git clone this repo & cd into it
    ```sh
    git clone git@github.com:mnyrop/fancy-feet.git && cd fancy-feet
    ```
2. Install correct Python version
    ```sh
    pyenv install --skip-existing
    ```
2. Install `pipenv`
    ```sh
    pip install pipenv
    ```
4. Install pip requirements with pipenv
    ```sh
    pipenv install
    ```
    > _**Note:** If there are any errors on this step, try clearing out any existing pipenv with:_
    > `pipenv --rm`
5. Launch Jupyter kernel
    ```sh
    pipenv run jupyter notebook
    ```
