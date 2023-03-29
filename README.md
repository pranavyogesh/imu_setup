# imu_setup
Setup and read data from mpu6050 IMU, then applying madgwick filter. Based on https://github.com/fsteinhardt/mpu6050_serial_to_imu and http://wiki.ros.org/imu_filter_madgwick

To run the ros nodes,
First upload the arduino sketch
roslaunch mpu6050_serial_to_imu demo.launch 
roslaunch mpu6050_serial_to_imu madgwick_filter.launch

