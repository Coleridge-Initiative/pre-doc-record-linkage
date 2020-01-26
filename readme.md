## Record Linkage


### In this repository
- This readme file contains the agenda for the 3-day training session
- [Notebooks](./Notebooks) - example notebooks we use in the training
- [Presentations](./Presentations) - presentations (will be added)

### set-up

The example notebooks use the Python `recordlinkage` package. You may be able to simply `pip install recordlinkage` to add it to your local machine

Optionally, anaconda provides a nice package management system and you can create virtual environments for different types of analyses. This [conda cheatsheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf) includes commands for setting up and creating virtual environments.

1. Create named env: `conda create --name py3-rl python=3.6`
2. Activate new env: `source activate py3-rl` (mac) or `conda activate py3-rl` (linux/windows)
3. Add recordlinkage: `pip install recordlinkage`
4. Add ipykernel for step 5:`conda install ipykernel`
5. Make kernel of new nev available to jupyter `python -m ipykernel install --user --name py3-rl --display-name "py3-RecLink"`
6. Launch Jupyter notebooks: `jupyter notebook`

Once you've run the above once, you should now have a `py3-RecLink` kernel available in your installation of Jupyter notebooks. If you need to add additional packages, you may need to repeat steps 2 (to reactivate the kernal) and steps 3 or 4 (to install the specific package(s)).

*_NOTE_* for the ML notebook example the sample data is too large to store on github, so we stored it on a Drive folder. You can [download it here](https://drive.google.com/drive/folders/1GyXYBVQOCqFndH6rM26ajoX3hhiyNg5M?usp=sharing)

### Additional resources
- [Patentview-API](https://github.com/Coleridge-Initiative/patentview-api) repository teaches API calls to pull PatentView data, and is built to work using [binder](https://mybinder.org/) so you do not need to install the required Python packages (`pandas` and `requests`)
