Tutorial of helicalPitch
=====

This is the tutorial of the helicalPitch. In this section, we will go through the pipeline of the helicalPitch with several examples, 
from the 2D class average image with short pitch to the image that does not include the whole pitch information. 


.. _BasicDatasethelicalPitch:

star file of the 2D classification result from the EMPIAR 10940 dataset
------------

1. Download the 2D class average from the EMPIAR-10940 dataset

.. code-block:: bash
    
    wget https://ftp.ebi.ac.uk/empiar/world_availability/10940/data/EMPIAR/Class2D/768px/run_it020_classes.mrcs
    wget https://ftp.ebi.ac.uk/empiar/world_availability/10940/data/EMPIAR/Class2D/768px/run_it020_data.star

2. Run the denovo3D helicalPitch with the following command:

.. code-block:: bash
    
    helicon helicalPitch

