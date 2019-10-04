# Setting up a Virtual Environment to Use Qiskit

Summary from [Python Packaging Docs](https://packaging.python.org/guides/installing-using-pip-and-virtualenv/).

(1) Install `virtualenv` if it is not already installed. (Note: There are different directions for Python 2.)

`python3 -m pip install --user --upgrade pip`
`python3 -m pip install --user virtualenv`

(2) Create a virtual environment.

Create a new directory and cd into it. Execute:

`python3 -m virtualenv envname`

(3) Activate the environment.

`source envname/bin/activate`

In the virtual environment, use `pip` to install packages as you would do normally.

`pip install qiskit`

You may need to handle other dependencies.

To leave the environment `envname`, run `deactivate` in the terminal.

