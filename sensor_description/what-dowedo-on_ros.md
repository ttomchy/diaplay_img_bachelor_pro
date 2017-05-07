# What do we do on ROS
>Since the main object of the ROS is to provide code reusing which is  good for robotics research and development.
ROS support a joint system similar to code repository, which can also achieve project collaboration and publishing. This design allows the development and im-plementation of a project from the file system to the user interface completely inde-
pendent decisions (without ROS limitation). At the same time, all projects can be
integrated by ROS basic tools.

  > In this project,we use the ROS to get the 3d data from the velodyne laser sensor.Then we publish the topic ,the publisher does not care who receive the topic . When the publish node get the data from the velodyne data ,then he will publish it quickly.We can use other open source software RVIZ to show the 3D data and the data can be shown as follows.
   [image](在这里要进行插图)

   >In addition, ROS has many useful tools. For example, in this project, we can use the  rviz visualization tool to view the input 3D data points, use the bag file to record data from the real environment and used rqt to draw the waveform of the output data.
