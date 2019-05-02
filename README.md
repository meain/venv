# venv

Easier workflow for python virutalenvs.

![screenshot](https://i.imgur.com/UETzhSG.png)


Dependencies:

- [`fzf`](https://github.com/junegunn/fzf) - Fuzzy file finder
- [`pyenv`](https://github.com/pyenv/pyenv) - Install any python version
- [`virtualenvwrapper`](https://virtualenvwrapper.readthedocs.io/en/latest/)* - Better virtualenv

## Installation

Copy over venv to somewhere in $PATH and make it executable.

```
curl 'https://raw.githubusercontent.com/meain/venv/master/venv' -o /usr/local/bin/venv
chmod +x /usr/local/bin/venv
```

## Usage

- Run `venv`
- Choose python version or choose `OTHER` to install new one from pyenv
- Name your virtualenv ( you could give the name along with the command like `venv myvenv` )
- You are good to go


## Configuration

You can set default python version by setting `DEFAULT_VENV_PYTHON_VERSION`.
So if you wanna use `3.7.1` do
```
DEFAULT_VENV_PYTHON_VERSION="3.7.1"
```

> Default is now set as `3.6.6`
