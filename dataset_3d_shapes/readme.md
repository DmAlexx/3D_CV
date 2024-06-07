# Simple 3d shapes detection
## dataset description

This folder contains files to generate 3D point clouds of indoor scenes from LIDAR data.
The root folder contains 3 sub-folders:
* cubes - contains 5 scenes with cubes
* cylinders - contains 5 scenes with cylinders
* planes - contains 4 scenes with planar objects

All objects in scenes placed vertically;

Each scene contains 4 files:
* frame.png - RGB frame
* depth.png - depth map, scale: 1m = 10,000units
* intrinsic.txt - 3x3 matrix with camera intrinsic parameters (focus distance, optical center)
* transform.txt - 4x4 matrix with camera transformation in world coordinates. You can use it to convert RGBD data to world coorinates

Coordinate system description: 
oY is up-vector
XoZ - horizontal plane
