# Py-env
Instructions to create a pyenv and document for future references.

### Useful commands:
- Check list of available versions: `pyenv install --list`
- Install a specific python version: `pyenv install -v 3.11.1`
- Location of the installed python version: `.pyenv/versions/3.11.1`
- So, installed versions can be checked using command: `ls ~/.pyenv/versions/`, or `pyenv versions`
- A Python version can be removed using commands: `rm -rf ~/.pyenv/versions/3.11.1` or `pyenv uninstall 3.11.1`
- Set the default version for python using command: `pyenv global 3.11.1`
- To get back the default to the system version, use: `pyenv global system`
