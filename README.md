This repository is a fork of Gabriel Harris' data science repo template.

For more details, read the Medium [article](https://medium.com/@drgabrielharris/python-how-using-poetry-make-and-pre-commit-hooks-to-setup-a-repo-template-for-your-ds-team-15b5a77d0e0f)


# How to use this data science repository template
Make sure you have WSL set up, pyenv installed and setup, and poetry installed.

The pyenv setup guide is decent; I plan to share my own. 

The poetry setup guide is quite good:
https://python-poetry.org/docs/ (do not ignore the step on adding poetry to your path.)

* Go to the repository on github.
* select the button "Use this template" and create a new repository.
* Git clone the new repository onto your local machine with WSL.
* Use the Makefile to create your virtual environment. Run in terminal: make setup
* Run source .venv/bin/activate to activate the virtual environment.
* Run make pre-commit

The make file creates a local directory which will not be committed to git.
You can use this directory for secrets and playgrounds that you will never commit.

The directory structure is just a suggestion and you are welcome to reformat the directories as suits your needs.

If you haven't already, add the Ruff extension to your vscode: https://marketplace.visualstudio.com/items?itemName=charliermarsh.ruff
