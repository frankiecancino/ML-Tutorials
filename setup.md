# Installation & Setup Steps
1. [Download and Install Python](#download--install-python)
2. [Create a Virtual Environment](#create-a-virtual-environment)
3. [Install Dependencies](#install-dependencies)
4. [Open a Jupyter Notebook](#open-a-jupyter-notebook)

## Download + Install Python
There are several different ways to download and install Python. My personal favorite is to use PyEnv (https://github.com/pyenv/pyenv)
<br />
Other methods include:
- [Python Website](https://www.python.org/downloads/)
- [Homebrew](https://brew.sh) with command: `brew install python`
- [Conda] (https://docs.conda.io/projects/conda/en/latest/index.html)

## Create a Virtual Environment
**This step is optional**<br />
After downloading and installing Python, we can create a virtual environment to keep the library versions specific to these ML tutorials. If you're not familiar with virtual environments, essentially we will be creating a Python environment with its own installed Python packages. What this does is separates your Python packages between projects. This way your projects won't clash due to incompatible versions. For example: one Python project requires a Python Package's version v0.1, but a different project requires the newer version v0.5.

In your terminal
1. If you don't have the library installed yet, or are not sure, run: `pip install virtualenv`
2. Create the virtual environment: `python -m venv ml_tutorials_venv`
3. Activate the virtual environment: `source ml_tutorials_venv/bin/activate`

## Install Dependencies
Now that we have Python installed and a virtual envrionment created, we can install the dependencies we need to make all of our code work. With your virtual environment activated, in your terminal run: `pip install -r requirements.txt`

## Open a Jupyter Notebook
You are ready to get started! All that's left is to open one of the notebooks in Jupyter Lab to run the code for yourself. If you haven't explored machine learning topics before, I suggest getting started with the [introductory notebook](https://github.com/frankiecancino/ML_Tutorials/blob/master/Intro_to_ML.ipynb). To open the notebook and run the code, run this command in your terminal (using your virtual environment) in the ML-Tutorials directory: `jupyter lab Intro_to_ML.ipynb`