# What is ROS ?

   >What is ROS ?
The Robot Operating System (ROS) is an open-source meta-operating system for
[robot](http://wiki.ros.org/ROS/Introduction).It provides necessary services for operation system,including the underlying device control and ,message passing between processes,hardware abstraction as well as package management. It also provides functions library for obtaining ,compiling ,writing codes. It can provides the services that you can execute your program among computers. It is a framework for robot.

>ROS running process is a loosely coupled peer-to-peer network based on ROS
communications infrastructure. ROS implements several different means of commu-
nication, including those based on synchronous RPC-style communication services
mechanism, based on asynchronous data streaming topics server mechanisms and
parameters server. Our project communication is based mainly on the topic mecha-
nisms. The goal of the Robot Operation System is to provide code reuse of the robot's research and development. the Robot Operation System is a distributed framework of processes.so the code can be designed individual .the processes can be grouped into a package which makes it is easily to be shared and distributed.Software for the Robot Operation System is currently test for ubantu and MAC OX X systems. So we choose ubantu as our platform for the Robot Operation System.

>The　basic  conception of the  ROS. There are many conceptions in the ROS. the node is a process which performs the computation.Usually ,a robot control system will contain many node. For instance ,we can use a node to control the motors ,use a node to get the 3D data from the laser sensor ,use a node performs localization, use one node to perform path planning ,and so on.Another conception is that the topic .the topic is named buses over which nodes exchange messages .As we have describe before ,the nodes are not  ware of who they are communicate with.Instead  nodes that are interested in data subscribe to the relevant topic; nodes that generate data publish to the relevant topic. There can be multiple publishers and subscribers to a topic. RVIZ is a 3D visualization tool for ROS.We can use RVIZ to build our robot and run our robot in a simulated environment.
