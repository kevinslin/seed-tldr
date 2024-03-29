---
id: common.jupytext
title: Jupytext
desc: ''
updated: 1642441815037
created: 1642441815037
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# jupytext

> Tool to convert Jupyter notebooks to plain text documents, and back again.
> More information: <https://jupytext.readthedocs.io>.

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

