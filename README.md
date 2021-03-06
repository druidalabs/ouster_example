# Linux instalation

## Step 1 
* sudo apt-get update 
* sudo apt-get install libvtk6-dev libeigen3-dev
* sudo apt-get install cmake
* sudo apt-get install dnsmask
* sudo apt-get install arp-scan

## Step 2
* compile the program as per OS-1 example
* configure dnsmask

# OS-1 Example Code
Sample code for connecting to and configuring the OS-1, reading and visualizing
data, and interfacing with ROS.

See the `README.md` in each subdirectory for details.

## Contents
* [ouster_client/](ouster_client/README.md) contains an example C++ client for the OS-1 sensor
* [ouster_viz/](ouster_viz/README.md) contains a visualizer for the OS-1 sensor
* [ouster_ros/](ouster_ros/README.md) contains example ROS nodes for publishing point cloud messages

## Sample Data
* Sample sensor output usable with the provided ROS code is available
  [here](https://data.ouster.io/sample-data-1.10)
