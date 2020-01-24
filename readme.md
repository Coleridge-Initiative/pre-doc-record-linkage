## Record Linkage


### In this repository
- This readme file contains the agenda for the 3-day training session
- [Notebooks](./Notebooks) - example notebooks we use in the training
- [Presentations](./Presentations) - presentations (will be added)

### set-up

The example notebooks use the Python `recordlinkage` package. You may be able to simply `pip install recordlinkage` to add it to your local machine

Optionally, anaconda provides a nice package management system and you can create virtual environments for different types of analyses. This [conda cheatsheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf) includes commands for setting up and creating virtual environments.

1. Create named env: `conda create --name py3-rl python=3.6`
2. Activate new env: `source activate py3-rl`
3. Add recordlinkage: `pip install recordlinkage`
4. Add ipykernel for step 5:`conda install ipykernel`
5. Make kernel of new nev available to jupyter `python -m ipykernel install --user --name py3-rl --display-name "py3-RecLink"`
6. Launch Jupyter notebooks: `jupyter notebook`
