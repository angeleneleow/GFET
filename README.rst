
.. image:: images/GFET_logo.png
  :width: 400
Geophysical Feature Extraction Toolkit (GFET)
========
.. image:: https://readthedocs.org/projects/geoana/badge/?version=latest
    :target: https://geoana.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status

.. image:: https://img.shields.io/github/license/simpeg/geoana.svg
    :target: https://github.com/simpeg/geoana/blob/master/LICENSE
    :alt: MIT license

.. image:: https://travis-ci.org/simpeg/geoana.svg?branch=master
    :target: https://travis-ci.org/simpeg/geoana
    :alt: Travis status

.. image:: https://api.codacy.com/project/badge/Grade/2e32cd28f4424dc1800f1590a64c244f
    :target: https://www.codacy.com/app/lindseyheagy/geoana?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=simpeg/geoana&amp;utm_campaign=Badge_Grade
    :alt: codacy status
    
This toolkit is a modification from an open-sourced tool called The Geophysical Toolkit for Geologists (GTG),
developed by UBC-GIF and MDRU. https://github.com/geoscixyz/Toolkit.

Getting Started
---------------
This tool only works for Windows users. (blame Geosoft)
Choose a preferred IDE to run your notebook. I'm using Visual Studio Code. 
If you do not already have python installed, we recommend downloading and installing it locally **without Anaconda**.
Install Geosoft Viewer for the Geosoft API to work (gxpy).
Read the documentation for more information on the functions of the toolkit. 

Install Geosoft Viewer
----------------------
You can download it `here `_ . 

2. Installing Python
-----------------
Currently, GFET runs on Python 3.7. We recommend that you use the latest version. 
(on Minerva's dekstop) Install the 64-bit version. 
TO complete the Python installation, make sure you enable *ADD TO PATH*  

.. image:: images/add-Python_to_Path.png
  :width: 400

Installing from source
-----------------------
To install GFET locally on your computer, 
create a new folder on your local disk
right click on the new folder and open in Visual Studio Code. 
Open a new terminal, type in

.. code::

    git clone http://git.minerva.local/aleow/gfet.git
..
 
 Dependencies  
 -------------
 Pip is the preferred way. I started off with conda and boy, times were difficult. 
 Some libraries were missing headers hence simply installation through pip would produce an error.
 To make it easier, i've included a zip file of all the site packages needed to be installed on the Z: drive. 
 (You can just copy and paste the folder into your local Python site-packages folder)
 .. code::

    pip install 
..
 numpy 
 scipy
 matplotlib
 jupyter
 sci-image
 

The complete list is available on 'requirements.txt' 

Running on Jupyter Notebook
---------------------------
On your terminal, type in 
.. code::

    jupyter notebook
..

To run every cell, press 

.. code::

  Ctrl + Enter 
  
..

License

GFET is licensed under the MIT license.
All other dependency libraries are licensed under MIT, BSD2 and BSD3.
