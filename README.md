# Udacity-Generative-AI-Nanodegree
This repository contains the project notebooks of Udacity's "Generative AI" Nanodegree.

## Installation, Dependencies and Starting the Notebook
The code of the projects was tested on Linux (Ubuntu 20.04). To get the code running on your local system, follow these steps which are base on Anaconda, pip and git:

### Download Repository
1. Go to a folder where you want to clone the repository.
2. In a bash terminal enter `git clone https://github.com/rp-dippold/Udacity-Generative-AI-Nanodegree.git`.

### Setting up Python environment for a Project
Enter the following commands in a bash terminal and enter the project number where necessary, e.g. replace <px> with p1:
1. `cd Udacity-Generative-AI-Nanodegree`
2. `conda create --name udacity_genai_<px> python=3.9.18 -c conda-forge`
3. `conda activate udacity_genai_<px>`
4. `python -m pip install --upgrade pip`
5. `python -m pip install -r requirements_<px>.txt`
7. `python -m ipykernel install --user --name udacity_genai_<px> --display-name "udacity_genai_<px>"`

### Start a Jupyter Notebook
1. Navigate to the project's folder.
2. Start the notebook by entering `jupyter-notebook` into the bash terminal.
3. Copy one of the displayed URLs, e.g. 'http://127.0.0.1:8888/?token=78c...' in a browser tab.
4. Select the notebook `<name>.ipynb` in your browser.
5. Select the kernel "udacity_genai_<px>" before running the cells.
