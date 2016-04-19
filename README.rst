==================================================================
distill: An analytical framework for User-ALE <https://github.com/draperlaboratory/user-ale>.
==================================================================

TODO: Modify the whole file as necessary.

This is a "long description" file for the package that you are creating.
If you submit your package to PyPi, this text will be presented on the `public page <http://pypi.python.org/pypi/python_package_boilerplate>`_ of your package.

Note: This README has to be written using `reStructured Text <http://docutils.sourceforge.net/rst.html>`_, otherwise PyPi won't format it properly.

Installation
------------

The easiest way to install most Python packages is via ``easy_install`` or ``pip``::

    $ easy_install distill

Development and Testing
------------
To build the source code and run all unit tests

	$ python setup.py develop test

To start up the web server, running on localhost:8090
	$ dev

Using curl
	$ curl http://localhost:8090/app/register' -d '{
		"application_name" : "my_app",
		"version" : "0.1",
		"application_description" : "my test app"
	}'

Usage
-----

TODO: This is a good place to start with a couple of concrete examples of how the package should be used.

The boilerplate code provides a dummy ``main`` function that prints out the word 'Hello'::

    >> from distill import main
    >> main()
    
When the package is installed via ``easy_install`` or ``pip`` this function will be bound to the ``distill`` executable in the Python installation's ``bin`` directory (on Windows - the ``Scripts`` directory).