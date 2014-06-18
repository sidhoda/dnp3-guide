Copyright (c) 2014 Automatak LLC


## Notice

This is a work in progress for the upcoming 2.0.x  release. Don't mistake this as complete documentation.


## About

This is the official documentation source to the [opendnp3 project](www.automatak.com/opendnp3).

It uses the [Sphinx](http://sphinx-doc.org/) documentation platform.

## Setup and Building

To build the documentation you'll need a working version of Sphinx. Follow the installation direction [here](http://sphinx-doc.org/latest/install.html) for your platform.

It also uses the [graphviz](http://www.graphviz.org/) Sphinx extension. The "dot" program needs to be on your PATH so Sphinx can run it. 
On Windows, the graphviz bin directory must be manually added to the PATH.

With Sphinx and graphviz installed:
		
```
make html
```
		
Documentation will be written to the /build folder.

