.. title:: AMSET

=======
AMSET
=======

Ab initio Model for Mobility and Seebeck coefficient using Boltzmann Transport equation.

More information here.

Scattering rates
----------------

More information about the scattering rates calculated in AMSET can be found :doc:`here </scattering>`.

===========
What's new?
===========

Track changes to AMSET through the :doc:`changelog`.

================================
Contributing / Contact / Support
================================

Want to see something added or changed? There are many ways to make that a reality! Some ways to get involved are:

* Help us improve the documentation - tell us where you got 'stuck' and improve the install process for everyone.
* Let us know if you need support for a queueing system or certain features.
* Point us to areas of the code that are difficult to understand or use.
* Contribute code! You can do this by forking `AMSET on Github <https://github.com/hackingmaterials/amset>`_ and submitting a pull request.

The list of contributors to AMSET can be found :doc:`here </contributors>`.

=======
License
=======

AMSET is released under a modified BSD license; the full text can be found :doc:`here</license>`.

============
Installation
============


Requirements
------------

* Python 3.6+
* NumPy
* SciPy
* BoltzTraP2

Install
-------

.. code-block:: bash

    $ # Download the repository and install
    $ git clone https://github.com/hackingmaterials/amset.git
    $ cd amset
    $ pip install -e .


Run tests
---------

.. code-block:: bash

    $ python setup.py test

================================
Changelog, contributors, license
================================

.. toctree::
    :maxdepth: 1

    changelog
    contributors
    license

==================
Code documentation
==================

Autogenerated code documentation below:

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
