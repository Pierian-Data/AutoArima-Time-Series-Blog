# Blog-Posts

This is the Repo for the Notebooks for our Blog Posts.

## Setup & Running

To run notebooks in this repo, you'll need to recreate the kernel used to
create them. You can do this quite simply. First, create the conda env by
navigating to the project directory and running:

```
$ conda env create -f env.yml
```

Then you'll need to register this environment as an ipython kernel ([1]). Use the
following command:

```
$ conda activate auto-arima
(auto-arima) $ python -m ipykernel install --user --name auto-arima --display-name "Auto-Arima (Py3)"
```

Now you'll be able to run the notebooks via Jupyter notebook or Jupyterhub.

If you don't have `conda` installed, you can get it with the `miniconda`
distribtution ([2]).

[1]: https://ipython.readthedocs.io/en/stable/install/kernel_install.html
[2]: https://conda.io/miniconda.html
