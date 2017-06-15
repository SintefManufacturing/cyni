cyni
=====

Cython-based wrapper for OpenNI2

This wrapper is incomplete, but will let you capture both depth and color images using OpenNI2's syncrhonous API. The asynchronous API is not implemented. Making this wrapper feature-complete wouldn't be too time consuming, so feel free to submit a pull request if you decide to do it.

Example of compilation in linux, setting variables manually:
sudo OPENNI2_INCLUDE=/usr/include/openni2/ OPENNI2_REDIST=/usr/lib/OpenNI2/ python3 setup.py build

