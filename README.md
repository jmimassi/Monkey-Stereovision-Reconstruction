# Monkey 3D reconstruction

## Description
This project focuses on implementing stereovision techniques in computer vision. Stereovision is a method that uses two or more cameras to create a 3D perception of the environment. The goal of this project is to develop algorithms and techniques to extract depth information from stereo image pairs.

## Steps
- Image rectification
- Disparity map generation
- Depth map estimation
- Point cloud visualization

The objective is to reconstruct a 3D object from the perspective of a 2D camera :
- This is the 3D object to reconstruct :
![alt text](main.png)

- This is 2 picture with a stereocamera of this object :
<div style="display: flex;">
    <img src="scanLeft/0000.png" alt="Left Image" style="width: 50%;">
    <img src="scanRight/scan0000.png" alt="Right Image" style="width: 50%;">
</div>

- This is the final reconstructed image :
![alt text](3D_reconstruction.png)