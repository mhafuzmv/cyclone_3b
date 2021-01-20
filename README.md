# cyclone_3b
Cyclone task 3B: 

## 2D Sensor View Object Detection & Tracking method

Velocity determination is object based in this approach.

The approximated 2D sensor view with a pixel array (theta,phi) with range values as pixel amplitude is the input image to the object detection stage of the pipeline.

The centroid of the object bounding box is used as the seed location to determine the depth at which the detected object is.

From the spherical coordinates (theta, phi, range) of the centroid we derive the (Y, Z, X) cartesian coordinates for the tracked object.
