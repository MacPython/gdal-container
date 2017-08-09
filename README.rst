################################################
Building a Docker image for building GDAL wheels
################################################

This builds a Manylinux_ Docker image, in which the GDAL libraries have been
built.  In turn, this allows the GDAL wheel building repository to build
wheels for different versions of Python, without timing out.

.. _manylinux1: https://www.python.org/dev/peps/pep-0513
