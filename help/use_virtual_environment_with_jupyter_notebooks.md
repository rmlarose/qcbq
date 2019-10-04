# Enabling the Virtual Environment for Jupyter Notebooks

Summary from [this article](https://anbasile.github.io/programming/2017/06/25/jupyter-venv/).

(1) In the virtual environment, install `ipykernel`:

`pip install ipykernel`

(2) Install a new kernel:

`ipython kernel install --user --name=projectname`

Now, a jupyter notebook can be started as is normally done. Inside the notebook, select the Kernel tab at the top, and under "Change kernel," select the kernel that was just installed. (Will be named whatever was put for `projectname`.)

