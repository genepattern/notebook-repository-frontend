# notebook-repository-frontend

This nbextension is a companion to the GenePattern Notebook extension and the Notebook Repository web service.
It provides a frontend to the provided Notebook Repository services.

# Installation

This nbextension can be installed in the following ways.

## Jupyter 5.2 or earlier

Check out notebook-repository-frontend from git and then run the following in the notebook-repository-frontend directory.

```
jupyter nbextension install repo
jupyter nbextension enable repo/js/main
jupyter nbextension enable --section=tree repo/js/main
```

## Jupyter 5.3 or later

In Jupyter 5.3 and later, instead of running the `jupyter nbextension enable` commands, you can instead copy repo.json to
`etc/jupyter/nbconfig/tree.d` and `etc/jupyter/nbconfig/notebook.d`.