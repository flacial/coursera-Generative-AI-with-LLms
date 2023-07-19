### Starting the lab

1. Run `./setup.sh` to install the required dependecies.

- If it doesn't run, make it an executable by running `chmod +x setup.sh`.

2. Run `jupyter notebook` while you're in the repo directory.
3. Start adjusting values and printing them to understand how it works.

### Errors

If you get any errors such as "pykeyboard-input 0.0.2.1 depends on pywin32", run the following:

pip uninstall jupyter
pip uninstall ipywidgets
pip install jupyter
pip install ipywidgets
