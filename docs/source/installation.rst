Installation
=====

Install the anaconda following the instructions at
https://docs.anaconda.com/anaconda/install/index.html.

To install helicon, first create a conda environment:
.. code-block:: console

   conda create -n helicon python=3.10
   conda activate helicon

Then install the helicon package from PyPI:

.. code-block:: console

   pip install "helicon[all] @ git+https://github.com/jianglab/helicon"
