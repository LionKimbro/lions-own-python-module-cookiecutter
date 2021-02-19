# lions-own-python-module-cookiecutter
highly opinionated personal cookie cutter for Python Modules -- packages, testing, CC0, invoke

This is Lion's Own Python Module Cookie-Cutter.

My priorities:
1. Make it easy to create *small* Python modules, and publish them to PyPI.
2. Keep the infrastructure as simple, and specific as possible.

I ONLY support:
- CC0 1.0 Universal license -- *always*
- setup.cfg -- *for configuration options*
- setup.py -- *for publishing and package control*
- pytest -- *with one single script to keep tests in*
- src/package -- *uses the package format, isolated within src ([(2014-05-25)](https://blog.ionelmc.ro/2014/05/25/python-packaging/))*

SUPPORTS:
- command-line bin-path program installation

DOES NOT support:
- CHOICES -- *I'm making a single choice, and sticking with it; my brain only has so much space*
- virtualenv maintenance -- *the Python modules produced are very small, with extremely limited dependencies; I can manage requirements.txt just fine*
- version auto-incrementers -- *I can't believe there are like x20 of these things; that's far too detailed to automate*
- de-linting, Black -- *admirable, but I'm not concerned with it*
- multi-Python version testing -- *I'm more interested in writing code than setting up elaborate testing environments*
- Python 2 -- *no loyalty; it's 2021 people*

Aspirations:
- using [Sphinx](https://www.sphinx-doc.org/en/master/) for documentation

If you want something else, by all means, fork, and call it something different than "lions-own-..."  I'm a big believer in [adaptable code](https://communitywiki.org/wiki/CodeAdaptation), over [reusable code](https://communitywiki.org/wiki/CodeReuse).

This is a living system; I will likely make changes with time.


# Reference

- ["Packaging Python Projects"](https://packaging.python.org/tutorials/packaging-projects/) -- the first guide I used to make a PyPI package
- ["The Joy of Packaging"](https://python-packaging-tutorial.readthedocs.io/en/latest/setup_py.html) -- detailed introduction to Python packages
- ["Packaging a python library" (2014-05-25)](https://blog.ionelmc.ro/2014/05/25/python-packaging/) -- advocates for use of a src/ directory

