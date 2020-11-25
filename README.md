# iml-project
Class project for Introduction to Machine Learning 2020.

### Development

Requires Python 3.8.5 and Poetry for dependency management. You can install Poetry with:

    curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python

If your system has Python 2 as default, you might have to install python-is-python3 for Poetry to work properly:

    sudo apt install python-is-python3
  
Install dependencies with:

    poetry install
  
Run jupyter notebooks with:
  
    poetry run jupyter notebook
