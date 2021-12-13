# Volumetric Data Visualization in VR

### Done By : Gaurav Ajay Bhokare
### Release Date : 13/12/2021
### Platforms : WebGL, Vrduino


## Project Abstract:
- Volumetric data like medical images can be very critically understood when seen in VR view i.e in an immersive environment. This project is an attempt to create a program and associated HMD hardware from scratch to do this task. This project works in phases and the works through each fundamental step. 

- There are many advanced softwares and AR/VR projects which do a stunning job of representing medical images to its finest detail and are helping many doctors in the disease diagnosis process.

- Goal of my project is to replicate a tiny version of these grand projects by implementing crucial parts of software and hardware.

- Inspiration for this project comes from the Image processing class which teaches a lot of processing algorithms which are generic and applicable to 3D data.

## Project Features:

1. Cube Marching: The most fundamental algorithm to render a volumetric data.

- Marching cubes is a computer graphics algorithm, published in the 1987 SIGGRAPH proceedings by Lorensen and Cline, for extracting a polygonal mesh of an isosurface from a three-dimensional discrete scalar field (the elements of which are sometimes called voxels). The applications of this algorithm are mainly concerned with medical visualizations such as CT and MRI scan data images, and special effects or 3-D modelling with what is usually called metaballs or other metasurfaces. The marching cubes algorithm is meant to be used for 3-D, the 2-D version of this algorithm is called the marching squares algorithm

2. Stereoscopic unwrapping: This is the gateway to take a rendered image into the VR environment.

- Producing a stereo pair is a relatively simple process; rather than simply rendering a single image, one creates two related images which may then be viewed on a stereo monitor, in a stereo slide viewer, or by using colored glasses and an appropriate display filter.

- Rayshade facilitates the rendering of stereo pairs by allowing you to specify the distance between the camera positions used in creating the two images. The camera position given in the rayshade input file defines the midpoint between the two camera positions used to generate the images. Generally, the remainder of the viewing parameters are kept constant.
 
3. Analyzing data: The HMD has a mounted IMU which provides user head movement inputs and accordingly the rendered data is updated.


## Images: 

- **Volume Rendering** 

 ![image 1](/VR-FinalProject/project1.png)
 
 ![image 2](/VR-FinalProject/project2.png)
 
 ![image 3](/VR-FinalProject/project3.png)


- **Stereo unwrap**
- coming soon .........


- **HMD integration**
- coming later in December End .........


## Link to video:

- [click here](https://drive.google.com/file/d/1y7BKcC6-yCj--G2MysSWc52Jzi189Yzf/view?usp=sharing)



## About:

- This idea of medical image process was an inspiration from the image process class which showcased analysis of 2D images through various algorithms and hinted on the fact that 3D data processing is full of opportunities.


-  This project is an attempt to understand Will Usher's implementation of cube marching and adapt it to VR environment.

#### Contact: bhokare.gaurav@utah.edu
###           rogelio@cs.utah.edu

