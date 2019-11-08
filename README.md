# Mogrifier LSTM

Recommended you use Python `3.7`.
You will need to make sure that your virtualenv setup is of the correct version of python.
We will be using *PyTorch*.

Please see below for executing a virtual environment.

```shell
cd MogrifierLSTM
pip3 install virtualenv # If you didn't install it
virtualenv -p $(which python3) ./venv_lstm
source ./venv_lstm/bin/activate

# Install dependencies
pip3 install -r requirements.txt

# View the notebook

# Deactivate the virtual environment when you are done
deactivate
```

## Work with IPython Notebook

To view the notebook, simply run the following command to start an ipython kernel.

```shell
# add your virtual environment to jupyter notebook
python -m ipykernel install --user --name=venv_lstm

# port is only needed if you want to work on more than one notebook
jupyter notebook --port=<your_port>

```

and then work on the `MogrifierLSTM.ipynb` notebook.
Check the python environment you are using on the top right corner.
If the name of environment doesn't match, change it to your virtual environment in "Kernel>Change kernel".
