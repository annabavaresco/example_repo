# Example repo

This is a simple example of how you can structure a repo in a handy way. 

Inlcude any python modules that you'd like to ba available in your 'internal package' within the folder `src`. Note that the folder needs to contain a file called `__init__.py` for you to ba able to install the package.

By running `pip install -e .` in your project environment, you'll be able to call functions and variables from the modules within `src` from anywhere in the repo (see example in `rsa/my_rsa_notabook.ipynb`).