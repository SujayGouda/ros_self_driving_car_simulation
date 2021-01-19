## Simulating and interfacing self-driving car sensors in ROS

### Sensors used:
* LIDAR
* GPS
* Stereo Camera
* Camera
* IMU
* Laser scanner
* Ultrasonic sensor

#### LIDAR:

Imported and interfaced Velodyne LIDAR plugin

Random objects have been placed using Gazebo

Sensors data visualization:

![alt text](https://github.com/SujayGouda/ros_self_driving_car_simulation/blob/master/img/lidar.png)

#### GPS:

GPS module OxTS is used for generating GPS co-ordinates as rostopic

#### Camera:

Built-in Gazebo plugins have been used as Stereo and Mono cameras

Visual feed of stereo camera in Gazebo:

![alt text](https://github.com/SujayGouda/ros_self_driving_car_simulation/blob/master/img/camera.png)

#### IMU:

Built-in Gazebo plugin for inertial measurement unit (IMU) is interfaced for determining robots orientation, linear acceleration, angular velocity

#### Laser Scanner:

Built-in Gazebo plugin for Laser scanner is interfaced  to detect any objects shape, size, orientation, distance, relative motion / relative velocity

Sensor data Visualization of Laser scanner detecting multiple objects:

![alt text](https://github.com/SujayGouda/ros_self_driving_car_simulation/blob/master/img/laser.png)


#### Ultra-sonic sensor:

Built-in Ultrasonic sensor from hector Gazebo plugins is interfaced for range sensing and obstacle avoidance

Visualization of Ultrasonic sensor data in Rviz:

![alt text](https://github.com/SujayGouda/ros_self_driving_car_simulation/blob/master/img/ultrasonic.png)


### Autonomous navigation:

Robotic car with hector slam running in Gazebo with a new world:

![alt text](https://github.com/SujayGouda/ros_self_driving_car_simulation/blob/master/img/robot_gazebo.png)

Visualizing robotic car sensor data in Rviz:

![alt text](https://github.com/SujayGouda/ros_self_driving_car_simulation/blob/master/img/robot_rviz.png)

Navigation and Mapping visualization of the new world by robotic car:

![alt text](https://github.com/SujayGouda/ros_self_driving_car_simulation/blob/master/img/robot_map.png)
