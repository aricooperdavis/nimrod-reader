# NIMROD_Reader
A python 3.x script to read Met Office composite radar scenes in the NIMROD format.

This should be able to read all three types of composite scene (UK @ 1km, UK @ 5km and Europe @ 5km) but the geotiff creation part of the library has only been tested with UK @ 1km data.

If you are a CEDA user then you can find NIMROD data data in: /badc/ukmo-nimrod/

Requires: Numpy, gdal

## Updates
This is a fork of the original NIMROD_Reader project that just wraps it up so that it can be installed as a module using PyPi. I don't know how useful this is to most people, but it is useful to me.

Note that, because GDAL relies on MSVC C++ binaries, PyPi can't install all your dependencies.