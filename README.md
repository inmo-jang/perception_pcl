# perception_pcl

## Point Cloud Filtering Examples

  
    
  Before launch any of the followings, you need to make sure that the camera input is properly remapped to `~input`
  
  (1) Voxel filtering: `roslaunch pcl_ros camera_voxel_grid.launch`
   * This example takes the camera pointcloud topic `/camera_astra/depth/points` and filter them into `/voxel_grid/output`.
   
  (2) Statistical outlier removal filtering: `roslaunch pcl_ros camera_statistical_outlier_removal.launch`
   * This example is based on (1), filtering to `statistical_outlier_removal/output`. 
    
  (3) Radius outlier removal filtering: `roslaunch pcl_ros camera_radius_outlier_removal.launch`
   * This example is based on (1), filtering to `radius_outlier_removal/output`. 



  
==================================
[![Build Status](https://travis-ci.org/ros-perception/perception_pcl.svg?branch=melodic-devel)](https://travis-ci.org/ros-perception/perception_pcl)

PCL (Point Cloud Library) ROS interface stack. PCL-ROS is the preferred
bridge for 3D applications involving n-D Point Clouds and 3D geometry
processing in ROS.
