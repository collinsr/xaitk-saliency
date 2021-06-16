Pending Release Notes
=====================


Updates / New Features
----------------------

Interfaces

* Added support for positive and negative saliency values as output by the
  saliency map generation interfaces.


Fixes
-----

Implementations

* Fix saliency map normalization in both ``OcclusionScoring`` as well as
  ``SimilarityScoring`` to disallow cross-class polution in the norm.
