#################
automate-openstax
#################

This project holds the documentation for the `Automate the Boring Stuff @
OpenStax` course.

How to build the docs
---------------------

This documentation is built using the `Sphinx project <http://www.sphinx-doc.org/en/master/>`_
and is altered to support github-pages.

First, make sure you are in the root directory.

Run the following ``make`` command to build the docs.

.. code-block:: bash

   make docs

You can go to the following directory to see the results ``./src/_build/html``
to see the results.

To build the docs for github pages, run the following ``make`` command.

.. code-block:: bash

   make github

This command will copy the build files into the directory that GitHub expects
them to be.
