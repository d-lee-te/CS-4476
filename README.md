# CS 4476/6476 - Introduction to Computer Vision (Fall 2023)
I took CS 4476 in the Fall of 2023.

Lectured by James Hays.

## About
[Official course listing page](https://oscar.gatech.edu/bprod/bwckschd.p_disp_detail_sched?term_in=202208&crn_in=88212).

This class was taught with Python and the PyTorch vision modules.

### Course Curriculum
Was unable to access syllabus.

### Projects
Similar to my [CS-3630 class](https://github.com/d-lee-te/CS-3630), these projects were given to use with wrapper files.

These wrapper files included .ipynb files (interative python notebooks) that I would have loved to throw into this repo, but I don't believe I'm allowed to.

As the next best description, I'll provide the steps taken to achieve each project.

1. Convolution and Hybrid Images
    1. Create filter/gaussian kernel
    2. Apply filter to image
    3. Create a hybrid image with modified filter
    4. Create a hybrid image model
    5. Create hybrid images using a dataset
    6. Applying the Convolution Theorem, implement a convolution operation

2. SIFT Local Feature Matching
    1. Implement a Harris Corner Detector operator
        - Find distintive points in images given 2 different pictures of the same iamge
        - Create feature vectors at each interest point
        - Match features
    2. Implement and apply Sift Feature Descriptor
        - Compute magnitues and orientations of image gradients

3. Camera Calibration
    1. Calculate camera projection matrix given corresponding 2D & 3D points
    2. Calculate camera center
    3. Solve for fundamental matrix using RANSAC (random sample consensus)

4. Recognition w/ Deep Learning
    1. Create and train a simplenet
         - Obtain a dataset
         - Transform dataset
         - Define model architecture w/ appropriate layers 
         - Define loss function
         - Create/initialize an optimizer
         - Train and test model
      
    2. In case of lack of sufficient training data, add jitter

5. Semantic Segmentation Deep Learning
    1. Using PSPNet, implement a bottleneck
    2. Create a PPM (pyramid pooling module) to aggregate context on images
    3. Adjust model network to lower stride and higher downsampling rate
    4. Apply to data and draw conclusions

### Debrief

# Disclaimer
As most of the course content belongs to either the College or the Professors, I am transcribing my work and assignments to record the course.

As such, many assignments and files **may not include detailed descriptions or solutions**. This is done to avoid violations, avoid doxing myself and others, and any number of other reasons. If, for any reason, the full repo must be accessed, all assignments, descriptions, solutions, and class files are stored in a private version of the repo (so contact me. If you're a current student, don't bother since I won't give you access and it wouldn't help you anyway xp).

If possible, portions of the class will be linked to a separate readme explaining more about the linked assignment/solution/description/other.

If there exist any honorcode violations or any problems/solutions are *too* in-depth, please contact me. The intention of each public class repo is to record my experience and assignments of each class taken.

