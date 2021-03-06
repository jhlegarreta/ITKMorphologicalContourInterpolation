ITKMorphologicalContourInterpolation
====================================

.. |CircleCI| image:: https://circleci.com/gh/KitwareMedical/ITKMorphologicalContourInterpolation.svg?style=shield
    :target: https://circleci.com/gh/KitwareMedical/ITKMorphologicalContourInterpolation

.. |TravisCI| image:: https://travis-ci.org/KitwareMedical/ITKMorphologicalContourInterpolation.svg?branch=master
    :target: https://travis-ci.org/KitwareMedical/ITKMorphologicalContourInterpolation

.. |AppVeyor| image:: https://img.shields.io/appveyor/ci/thewtex/itkmorphologicalcontourinterpolation.svg
    :target: https://ci.appveyor.com/project/thewtex/itkmorphologicalcontourinterpolation

=========== =========== ===========
   Linux      macOS       Windows
=========== =========== ===========
|CircleCI|  |TravisCI|  |AppVeyor|
=========== =========== ===========


Overview
--------

An `ITK <http://itk.org>`_-based implementation of morphological contour
interpolation based off the paper:

  Albu AB1, Beugeling T, Laurendeau D.
  "A morphology-based approach for interslice interpolation of anatomical slices from volumetric images."
  IEEE Trans Biomed Eng.
  2008 Aug;55(8):2022-38.
  doi: 10.1109/TBME.2008.921158.

Documentation can be found in the `Insight Journal article
<http://www.insight-journal.org/browse/publication/977>`_::

  Zukić D., Vicory J., McCormick M., Wisse L., Gerig G., Yushkevich P., Aylward S.
  "ND Morphological Contour Interpolation",
  The Insight Journal. January-December, 2016.
  http://hdl.handle.net/10380/3563
  http://insight-journal.org/browse/publication/977

Installation
------------

Since ITK 4.11.0, this module is available in the ITK source tree as a remote
module. To enable it, set::

  Module_MorphologicalContourInterpolation:BOOL=ON

in ITK's CMake build configuration.

Python
^^^^^^

To install the Python packages::

  python -m pip install --upgrade pip
  python -m pip install itk-morphologicalcontourinterpolation


License
-------

This software is distributed under the Apache 2.0 license. Please see
the *LICENSE* file for details.


Acknowledgements
----------------

This work is supported by NIH grant R01 EB014346, "Continued development and
maintenance of the ITK-SNAP 3D image segmentation software."
