# TOOL ROAD
From a background model to detect the vehicles that pass through the toll, it is sought to obtain the number of the license plate and the city.



Background & Foreground Extraction
==========

The idea of extracting the foreground is to identify the objects that are not part of the background, i.e., the objects different from those present in the static scene.


Gaussian Mixture-based Background Subtraction
--------------------

<p align="center">
  <img src="https://cstopics.github.io/cstopics/assets/img/vision/7_mog.png" width="350"/>
</p>

Simple Thresholding
==========

Here, the matter is straight forward. If pixel value is greater than a threshold value, it is assigned one value (may be white), else it is assigned another value (may be black). The

<p align="center">
  <img src="https://cstopics.github.io/cstopics/assets/img/vision/4_structures.png" width="650"/>
</p>

Adaptive Gaussian Thresholding
--------------------

<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSmKpr6K4YhbSKnvY0w1o6EOVX8M8N9w_JjYfOWfafoDgk0lD05" width="350"/>
</p>

Transformations
==========
Geometric transformations modify the spatial relationship between pixels in an image. Suppose an input space $(w, z)$ and an output space (x, y), that are coordinate systems.


<p align="center">
  <img src="https://raw.githubusercontent.com/cstopics/cstopics/6937cd1177395c72b3ccd049293327d8097dc114/assets/notebooks/vision/geo_trans.png" width="450"/>
</p>

Projective transformation
--------------------


<p align="center">
  <img src="https://raw.githubusercontent.com/cstopics/cstopics/6937cd1177395c72b3ccd049293327d8097dc114/assets/notebooks/vision/fig_projective.png" width="250"/>
</p>
