# Churn-Prediction


Pre-requisites

Creating a virtual environment using Anaconda. If you need to create your workflows in Python and keep the dependencies separated out or share the environment settings, Anaconda distributions are a great option.
The following main Python-based libraries have been used :

Flask
Numpy
Pandas
Tensorflow
Keras
which will be installed during setting the environment.

Provided the requirements are already installed in your system , you can simply execute the .py script named flask_app.py However, for future deployment purposes it is essential to create a virtual environment.

Step 1 : Main Directory

Go to command prompt/terminal (for Linux users) and change to the project as the default directory. Example: If current path is C:\Users\name> change to C:\Users\name>cd Desktop\flasksite (if downloaded to Desktop)

Step 2 : Create environment

Create a conda environment using conda create -n env This will create an empty Python environment with name env . Activate using activate env To exit from the virtual environment , simply execute deactivate env For further information , you can refer here

Step 3 : Install required libraries

Anaconda distribution comes with many default downloaded libraries which the user can directly , however to efficiently manage the environment , manually install libraries. A simple way would be to use pip - Python default package manager pip install [nameOfPackage] Install the libraries specified in pre-requisites Example:

pip install flask
pip install numpy
For more information about pip you can refer documentation

Step 4 : Execute script

When all python dependencies are installed , simply execute the .py script named flask_app.py
python flask_app.py in the cmd prompt should do the task. Follow the link generated, and the flask code should be up and running !
