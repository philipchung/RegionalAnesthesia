# Regional Anesthesia

Regional Anesthesia Jupyter Book for UW Anesthesia Peer Talk 9/19/2022.

## Dependencies

This presentation is made with JupyterBook (<https://jupyterbook.org/en/stable/intro.html>).

```sh
conda create -n regional python=3.8
conda activate regional
pip install -U jupyter-book ghp-import
```

To build JupyterBook from source:

```sh
# Build jupyter book from source files.  Output is in /presentation/_build
jupyter-book build presentation
# Publish to Github Pages (copies _build/html to gh-pages branch)
ghp-import -n -p -f presentation/_build/html
```
