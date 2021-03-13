---
id: common.jupytext
title: Jupytext
desc: ''
updated: 1615655543065
created: 1615655543065
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# jupytext

> Tool to convert Jupyter notebooks to plain text documents, and back again.
> More information: <https://jupytext.readthedocs.io/en/latest/>.

- Turn a notebook into a paired `.ipynb`/`.py` notebook:

`jupytext --set-formats ipynb,py {{notebook.ipynb}}`

- Convert a notebook to a `.py` file:

`jupytext --to py {{notebook.ipynb}}`

- Convert a `.py` file to a notebook with no outputs:

`jupytext --to notebook {{notebook.py}}`

- Convert a `.md` file to a notebook and run it:

`jupytext --to notebook --execute {{notebook.md}}`

- Update the input cells in a notebook and preserve outputs and metadata:

`jupytext --update --to notebook {{notebook.py}}`

- Update all paired representations of a notebook:

`jupytext --sync {{notebook.ipynb}}`

