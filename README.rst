Genweb 5-buildout
====================

This is the ultimate-uber-maxi-definitive-awesomefull buildout for Genweb-based
projects.

Usage
-----

You should choose what project do you want to work with or the basis of your new
one. For example, if you want to use a GenwebUPC buildout you should specify the
name of the project .cfg associated:

.. code-block:: bash

 $ [path_to_your_python_bin] bootstrap.py -c genwebupc.cfg --setuptools-version=42.0.2 --buildout-version=2.13.4
 $ cp customizeme.cfg.in customizeme.cfg
 $ ./bin/buildout -N -c genwebupc.cfg

Check out for the available projects in the projects.cfg file.

.. note:: Before that, remember to copy the customizeme.cfg.in file into customizeme.cfg configuring the required parameters.

Available projects/builds
-------------------------
* Genweb UPC
   - genwebupc.cfg
