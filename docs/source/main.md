# test-repo

This repo is for testing out the functionality of using sphinx to create documentation. 

# Steps:
1. Install poetry
2. `poetry shell`
3. Run `sphinx-quickstart` to set up the basic structure
3. Add extension for parsing markdown `poetry add myst-parser` 
4. Add `myst_parser` as an extension in `conf.py`
5. Add a random readme file called `license.md`
6. Edit `index.rst` file like below: 

```
.. toctree::
   :maxdepth: 2

   license.md

```

7. run `make html` again
8. open `index.html` to see the documentation being built
9. see example [here](https://github.com/serra/sphinx-with-markdown)