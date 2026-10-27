# Setup for the Bayesian Modeling Homework
PSY/COS 360, Computational Models of Cognition

This assumes you already have Python and the `ccm` conda environment set up
(from the Categorization homework or elsewhere). If you don't have `ccm` yet,
see the setup steps in [homework-Categorization/README.md](../homework-Categorization/README.md)
first, then come back here.

## 1. Install the dependencies

In the terminal, go to this folder (the one with `requirements.txt`):

```
cd path/to/homework-Bayes
```

Then:

```
conda activate ccm
pip install -r requirements.txt
```

Run `conda activate ccm` again each time you open a new terminal for this
homework.

## 2. Open the notebooks

From this folder, with `ccm` activated:

```
jupyter notebook
```

Your browser opens a file list. Click `Homework-Bayes-A.ipynb` to start,
then run cells top to bottom with Shift+Enter. Do the same with the others.

Keep all the files in this folder together so the notebooks can display
the figures in `images/`.

## If a notebook says a package is missing

The notebook may be using the wrong Python. Close Jupyter, run
`conda activate ccm`, then `jupyter notebook` again from this folder. Still
stuck? Post on the Ed forum with the exact command and full error text.