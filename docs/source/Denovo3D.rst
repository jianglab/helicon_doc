Tutorial of denovo3D
=====

This is the tutorial of the denovo3D. In this section, we will go through the pipeline of the denovo3D with several examples, 
from the 2D class average image with short pitch to the image that does not include the whole pitch information. 


.. _BasicDataset3D:

2D class deposited in the EMPIAR-10940 dataset
------------

1. (optional) Download the 2D class average from the EMPIAR-10940 dataset

.. code-block:: bash
    
    wget https://ftp.ebi.ac.uk/empiar/world_availability/10940/data/EMPIAR/Class2D/768px/run_it020_classes.mrcs

2. Run the denovo3D helicon with the following command:

.. code-block:: bash
    
    helicon denovo3D

3. There is an option to select "How to obtain the input image", one can upload the 2D class average image just downloaded or select the 
URL and put the following URL:
.. code-block:: bash
    https://ftp.ebi.ac.uk/empiar/world_availability/10940/data/EMPIAR/Class2D/job010/run_it020_classes.mrcs


4. Select an image on the left panel.

5. On the right side, there is a transform panel, one can either click the 'Auto transform' button to automatically transform the image, 
or manually adjust the parameters in the transform panel. One need to make sure that the helical image is aligned with the equitor line.
Like the following image:

.. image:: ../image/denovo3D_transform.png
    :width: 600px
    :align: center

6. Select the searching range for the helical rise and twist.

7. Click the 'Run' button to start the denovo3D analysis.

Low twist 2D class average image
----------------

Download the 2D class average from the zenodo:

.. code-block:: bash
    
    wget https://zenodo.org/record/15800626/helicon/low_twist_class.mrcs


