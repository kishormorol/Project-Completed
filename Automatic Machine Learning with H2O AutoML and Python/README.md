This .zip file contains all the code and data used in the project. It includes the bank marketing data set, completed Jupyter notebook for training, a Pipfile to manage the required libraries. Please feel free to modify any and all aspects of the code to suit your needs. If you don't want to use the pipfile, make sure to pip install jupyterlab, h2o, pandas, numpy, matplotlib, xlrd

Project.zip
Java is always required to run H2O. Supported versions include: Java 8, 9, 10, 11, 12, and 13. To build H2O or run H2O tests, the 64-bit JDK is required. Both of these are available on the Java download page.  If you have any issues with H2O installation, please refer to the official documentation.

Once you have downloaded and extracted Project.zip and have installed Java, make sure to install dependencies using pipenv with the provided Pipfile and execute all commands using pipenv. Next, to install pipenv, the dependencies, execute the following commands from your terminal or command prompt, making sure to add the right paths where necessary:

cd \path\to\Project\
pip install pipenv
pipenv install
pipenv run jupyter lab
