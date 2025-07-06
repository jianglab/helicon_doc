Tutorial of denovo3D
=====

This is the tutorial of the denovo3D. In this section, we will go through the pipeline of the denovo3D with several examples, 
from the 2D class average image with short pitch to the image that does not include the whole pitch information. 


.. _BasicDataset3D:

2D class deposited in the EMPIAR-10940 dataset
------------

Download the 2D class average from the EMPIAR-10940 dataset

.. code-block:: bash

   wget wget https://ftp.ebi.ac.uk/empiar/world_availability/10940/data/EMPIAR/Class2D/768px/run_it020_classes.mrcs

run the denovo3D helicon with the following command:

.. code-block:: bash
    helicon denovo3D

One can play with the parameters of the denovo3D


Low twist 2D class average image
----------------



