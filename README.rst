Modified Version: Run the codes below. 

::

 git clone https://github.com/Joeclinton1/google-images-download.git
::

 cd google-images-download && sudo python setup.py install #
 
Example Python codes

.. code-block:: xml

  from google_images_download import google_images_download   #importing the library

  response = google_images_download.googleimagesdownload()   #class instantiation

  arguments = {"keywords":"Polar bears,baloons,Beaches","limit":20,"print_urls":True}   #creating list of arguments
  paths = response.download(arguments)   #passing the arguments to the function
  print(paths)   #printing absolute paths of the downloaded images

Google Images Download
######################

Python Script for 'searching' and 'downloading' hundreds of Google images to the local hard disk!

Documentation
=============

* `Documentation Homepage <https://google-images-download.readthedocs.io/en/latest/index.html>`__
* `Installation <https://google-images-download.readthedocs.io/en/latest/installation.html>`__
* `Input arguments <https://google-images-download.readthedocs.io/en/latest/arguments.html>`__
* `Examples and Code Samples <https://google-images-download.readthedocs.io/en/latest/examples.html#>`__


Disclaimer
==========

This program lets you download tons of images from Google.
Please do not download or use any image that violates its copyright terms.
Google Images is a search engine that merely indexes images and allows you to find them.
It does NOT produce its own images and, as such, it doesn't own copyright on any of them.
The original creators of the images own the copyrights.

Images published in the United States are automatically copyrighted by their owners,
even if they do not explicitly carry a copyright warning.
You may not reproduce copyright images without their owner'self permission,
except in "fair use" cases,
or you could risk running into lawyer'self warnings, cease-and-desist letters, and copyright suits.
Please be very careful before its usage! Use this script/code only for educational purposes.
