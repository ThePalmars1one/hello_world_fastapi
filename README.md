# HELLO WORLD (FastAPI)
As the description says, it is simply a "Hello World" using FastApi and Python. By following the steps below, the result you should get in your browser is as follows:

<p align= center >
<img src="https://i.postimg.cc/vZLtgw13/hello-py.png">
</p>

First you need to clone the repository with the command:

git clone https://github.com/ThePalmars1one/hello_world_fastapi.git

After you have cloned the repository, you must verify that you have PIP installed, if you are using Python 2.7.9 (or higher) or Python 3.4 (or higher), then PIP comes installed with Python by default. To check the version, the command is:

pip --version

## VENV
After following these steps you must create a virtual environment and activate it:

1. python -m venv venv_name

2. source venv_name/Scripts/activate (GIT BASH)

To deactivate the environment just type in the console: deactivate.

## Requirements.txt
The next step would be to install all the packages required in the project, which are described in the requirements.txt, with the following command and run it:

1. pip install -r requirements.txt

2. uvicorn main:app --reload

