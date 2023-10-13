# statistical-learning
This repository contains programs that implement various techniques in the broad field of statistical learning.

# main steps (windows OS)
1) Download python 3 from https://www.python.org/downloads/release/python-3107/.
2) Find the Environmental Variable settings page and add path_to_python/Scripts/ to the PATH user variable.
3) [Command line] Create a new virtual environment (market_microstructure) by prompting: python -m venv /path/to/new/virtual/environment/statistical_learning/
4) [Command line] Activate the virtual environment by changing the current directory to -m venv /path/to/new/virtual/environment/statistical_learning/Scripts and then prompt activate.bat
5) Ensure that a requirements.txt file containing all the python packages required for this project is in the project folder. This file must have the following format
   package1==version
   package2==version
   packagek==version
6) [Command line] Prompt pip install -r requirements.txt to install the required packages in the active virtual environment. There is no need to perform this step again if the required packages have been previously installed.er