Object detection and tracking process using a pre-trained model for detection. The focus of this project is more on using the detections as a priori information to track objects moving through camera frames. 

Note: This was mostly tested on camera feeds of people a few metres from the camera, so there may be some lag when using it for front-on webcam testing. The tracking algorithm used is the Kalman Filter for adaptive gaussian based motion prediction. 

- Will add more details later.

References for filter design:
https://github.com/rlabbe/Kalman-and-Bayesian-Filters-in-Python
https://github.com/kcg2015/Vehicle-Detection-and-Tracking
https://arxiv.org/pdf/1910.03558.pdf
