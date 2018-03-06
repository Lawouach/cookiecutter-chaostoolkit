======================
Cookiecutter Chaos Toolkit
======================

Cookiecutter_ template for the Chaos Toolkit Extensions.

Based on the `cookiecutter-pypackage`_.

Free software: BSD license


Quickstart
----------

Install the latest Cookiecutter if you haven't installed it yet (this requires
Cookiecutter 1.4.0 or higher)::

    pip install -U cookiecutter
    
Alternatively, to install the `cookiecutter` package in OSX:
    
    brew install cookiecutter
    
Generate a Chaos Toolkit Extension project::

    cookiecutter https://github.com/dastergon/cookiecutter-chaostoolkit.git

Then:

* Create a repo and put it there.
* Add the repo to your Travis-CI_ account.
* Install the dev requirements into a virtualenv. (``pip install -r requirements_dev.txt``)
* Register_ your project with PyPI.
* Run the Travis CLI command `travis encrypt --add deploy.password` to encrypt your PyPI password in Travis config
  and activate automated deployment on PyPI when you push a new tag to master branch.
* Release your package by pushing a new tag to master.
* Add a `requirements.txt` file that specifies the packages you will need for
  your project and their versions. For more info see the `pip docs for requirements files`_.
* Activate your project on `pyup.io`_.

.. _`cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage/
.. _`pip docs for requirements files`: https://pip.pypa.io/en/stable/user_guide/#requirements-files
.. _Register: https://packaging.python.org/distributing/#register-your-project

