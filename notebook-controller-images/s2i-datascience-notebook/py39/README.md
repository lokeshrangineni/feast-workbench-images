# Python 3.9 Minimal Notebook

This recipe is tagged as Python 3.9 because of the Pipfile that fixes the Python version.

Build example  from UBI9 with Python 3.9:

```bash
make ubi9-py39 BASE_IMAGE=localhost/s2i-minimal-notebook-ubi9-py39:0.0.1 TAG=0.0.1
```

Build example  from UBI8 with Python 3.9:

```bash
make ubi8-py39 BASE_IMAGE=localhost/s2i-minimal-notebook-ubi8-py39:0.0.1 TAG=0.0.1
```