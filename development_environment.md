## Development Environment

To have a uniform development environment across platforms and machines, we will use both `pyenv` and `pipenv` to achieve that.

### 1\. pyenv - Python version management
It allows users to configure the python version they want to work with.

+ [How it works](https://github.com/pyenv/pyenv#how-it-works)
+ [Installation](https://github.com/pyenv/pyenv#installation)
+ [Which Python Package Manager Should You Use?](https://www.youtube.com/watch?v=3J02sec99RM)

Once `pyenv` is installed, use the following command to install and select default python version.
```bash
# list all available python
pyenv install --list

# install a particular version for the project.
# python 3.8.5 is the one we will use in our project
pyenv install 3.8.5

# change default python to be 3.8.5
pyenv global 3.8.5

# check python version. Make sure it's Python 3.8.5
python --version
```

### 2\. pipenv - Python package manager
It allows users to install python packages in a virtual environment. It will create `Pipfile` and `Pipfile.lock` files in the project folder.

+ [Pipenv: Python Development Workflow for Humans](https://github.com/pypa/pipenv)

```bash
# install pipenv with pip
# pip is the default python package manager.
# Once pipenv is installed, future packages needed in the project can be installed through pipenv
pip install pipenv

# install packages for the project
pipenv install
```

### 3\. `jupyter` notebook

There are multiple ways to run the jupyter notebook.

1\. Jupyter NoteBook + Browser

```bash
# make sure jupyter runs in virtual environment
pipenv shell

# jupyter will open a web page and render the notebook in the browser
jupyter notebook
```

2\. VS Code + Jupyter Extension

3\. Other IDEs

+ [Jupyter Tips and Tricks](https://www.youtube.com/watch?v=2eCHD6f_phE)


### 4\. `pyspark`, `dask`, `ray` or others

// todo
