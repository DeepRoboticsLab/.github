<img src="https://www.deeprobotics.cn/public/static/robot/images/logo_.png" alt="Deep Robotics" style="width: 25%;">

[![bilibili](https://img.shields.io/badge/bilibili-f87598?style=flat&logo=bilibili&logoColor=white&labelColor=f87598&color=f87598)](https://space.bilibili.com/22477177)
[![linkedin](https://img.shields.io/badge/Linkedin-1465bd?style=flat&logoColor=white&labelColor=1465bd&color=1465bd)](https://cn.linkedin.com/company/deep-robotics)
[![YouTube](https://img.shields.io/badge/YouTube-%23ff1a47?style=flat&logo=Youtube&labelColor=%23ff1a47)](https://www.youtube.com/@deeprobotics8601)
[![X](https://img.shields.io/badge/Twitter-black?style=flat&logo=X&labelColor=black)](https://x.com/DeepRobotics_CN)

DEEPRobotics is a national high-tech enterprise that focuses on the R&D, production, sales and service of humanoid robots, quadruped robots, and core components.
The company has always adhered to independent innovation, with core technologies such as advanced control algorithms, intelligent environmental perception, and artificial intelligence algorithms at the forefront of international development.

### Projects

<table style="width: 100%; table-layout: fixed; border-collapse: collapse;">
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>

  <tr>
    <td align="center"><a href="https://github.com/DeepRoboticsLab/URDF_model"> URDF_model </a></td>
    <td> Robot's URDF model.
    </td>
  </tr>

  <tr>
    <td align="center"><a href="https://github.com/DeepRoboticsLab/Lite3_MotionSDK"> Lite3_MotionSDK </a></td>
    <td> SDK for the Jueying <b><i>Lite3</b></i> motion control algorithm.
    <br> Get the data of each joint and send joint control command to control the robot to move, provides control parameters to control the motion of joints.
    <br> Supports <a href="https://github.com/DeepRoboticsLab/Lite3_MotionSDK">C++</a> and <a href="https://github.com/DeepRoboticsLab/Lite3_MotionSDK/tree/add_python">Python</a>.
    </td>
  </tr>

  <tr>
    <td align="center"><a href="https://github.com/DeepRoboticsLab/Lite3_ROS"> Lite3_ROS </a></td>
    <td> Conversion between ROS and UDP messages.
    <br> Implement data transmission between the Jueying <b><i>Lite3</b></i> perception host and the motion host or app via the UDP protocol.
    <br> <a href="https://github.com/DeepRoboticsLab/Lite3_ROS"> ROS-Ubuntu20 </a>,<a href="https://github.com/DeepRoboticsLab/Lite3_ROS/tree/ubuntu18"> ROS-Ubuntu18 </a>,<a href="https://github.com/DeepRoboticsLab/Lite3_ROS/tree/ros2-foxy"> ROS2-foxy-Ubuntu20 </a>
    </td>
  </tr>

  <tr>
    <td align="center"><a href="https://github.com/DeepRoboticsLab/Lite3_rl_training"> Lite3_rl_training </a></td>
    <td> A Learning-based locomotion controller for quadruped robots. 
    <br> Includes all components needed for training and hardware deployment on DeepRobotics <b><i>Lite3</b></i>.
    </td>
  </tr>
  
  <tr>
    <td align="center"><a href="https://github.com/DeepRoboticsLab/Lite3_rl_deploy"> Lite3_rl_deploy </a></td>
    <td> A policy trained by RL.
    <br> The methods for deploying and validating the policy in the simulation environment or on the <b><i>Lite3</b></i>.
    </td>
  </tr>
  
  <tr>
    <td align="center"><a href="https://github.com/DeepRoboticsLab/x30_motion_sdk"> x30_motion_sdk </a></td>
    <td> SDK for the Jueying <b><i>X30</b></i> motion control algorithm.  
    <br> Provides control parameters to control the motion of joints.
    <br> Supports C++ and Python.
    </td>
  </tr>
  
  <tr>
    <td align="center"><a href="https://github.com/DeepRoboticsLab/gamepad"> gamepad </a></td>
    <td> Listening for physical button trigger events on the gamepad via UDP communication on the remote host.
    <br> Real-time acquisition of physical button trigger information from the gamepad side.
    </td>
  </tr>

  <tr>
    <td align="center"><a href="https://github.com/DeepRoboticsLab/Deep_Motor_SDK"> Deep_Motor_SDK </a></td>
    <td> The SDK provides CAN communication, joint enablement, and joint control functions for <b><i>J60</b></i>. 
    <br> Includes examples for <b><i>single-joint</b></i>, <b><i>multi-joint control</b></i>, and <b><i>joint debugging tool software</b></i>.
    </td>
  </tr>

  <tr>
    <td rowspan="2" align="center"><a href="https://github.com/DeepRoboticsLab/Lite3_Model_Control"> Lite3_Model_Control </a></td>
    <td><a href="https://github.com/DeepRoboticsLab/Lite3_Model_Control/tree/main/basic_level_sim"> basic_level_sim </a>
    <br> A basic simulation project implemented based on the Jueying Lite3 <a href="https://github.com/DeepRoboticsLab/Lite3_MotionSDK">MotionSDK</a> and the <a href="https://gazebosim.org/">Gazebo</a> simulation platform.</td>
  </tr>
    <td><a href="https://github.com/DeepRoboticsLab/Lite3_Model_Control/tree/main/high_level_sim"> high_level_sim </a>
    <br> A high level simulation project ported and optimized based on the Ascend open-source project <a href="https://gitee.com/HUAWEI-ASCEND/quadruped-robot/tree/master/model-control">model-control/quadruped-robot</a>, and implemented on the <a href="https://gazebosim.org/">Gazebo</a> simulation platform.</td>

</table>
