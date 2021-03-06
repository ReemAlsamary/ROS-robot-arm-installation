# ROS-robot-arm-installation
Install and run the Robot arm on ROS(Robot operating system).
# Steps:
### 1. Start a new project by signing up at https://www.theconstructsim.com/, then the following page will show once you click on Create a Project, then fill in the boxes with the project name, the ROS version you wish to use (I'm using ROS Melodic), and a brief description before clicking Create.

<img width="1270" alt="Screen Shot 1442-12-06 at 2 33 33 AM" src="https://user-images.githubusercontent.com/86277104/126019373-810a0a27-a3ce-490c-85c8-cdd2ead24187.png">

---
### 2. Installing the Robot Arm package from the Smart Methods github by using the command ($ sudo apt install git) to install Github on ROS.                               
<img width="812" alt="Screen Shot 1442-12-06 at 2 37 01 AM" src="https://user-images.githubusercontent.com/86277104/126022135-d9fcf39c-6a3c-4e50-aa75-d6b224c7247d.png">

---	
### 3. Installing the dependencies (moveit,joint state puplisher,gazebo) on ROS by using the following commands, then compile the package after the installation is completed.

<img width="992" alt="Screen Shot 1442-12-06 at 2 42 59 AM" src="https://user-images.githubusercontent.com/86277104/126020045-597ae532-93a3-4843-8593-6fdf5d2d394c.png"> <img width="874" alt="Screen Shot 1442-12-06 at 2 43 16 AM" src="https://user-images.githubusercontent.com/86277104/126020073-3c07607a-97bc-41d2-880e-684c682b2b61.png">


---
### 4. Controling the motor in simulation by using the ($ roslaunch robot_arm_pkg check_motors.launch), ($ roslaunch robot_arm_pkg check_motors_gazebo.launch) command to launch the Robotic Arm control on both RVis and Gazebo and adjust the arm using the controls.

<img width="956" alt="Screen Shot 1442-12-06 at 2 49 17 AM" src="https://user-images.githubusercontent.com/86277104/126020238-0ce4918d-a23f-449e-bcae-98634e2b1f9c.png"> <img width="868" alt="Screen Shot 1442-12-06 at 2 48 49 AM" src="https://user-images.githubusercontent.com/86277104/126022159-27bea035-85b3-4747-a92b-1d1074f0ca53.png"> <img width="681" alt="Screen Shot 1442-12-07 at 1 03 08 AM" src="https://user-images.githubusercontent.com/86277104/126020500-894c83ac-08ce-4a10-a505-b12d2edfc1b5.png">


---
### 5. MoveIt in RVis by using the ($ roslaunch moveit_pkg demo.launch) command to simulates the arm movement in different directions which will result as shown in the following windows:

<img width="983" alt="Screen Shot 1442-12-07 at 1 24 02 AM" src="https://user-images.githubusercontent.com/86277104/126020877-bd1bcfd7-3735-44c3-b6c4-003c715a3e92.png"> <img width="975" alt="Screen Shot 1442-12-07 at 1 24 09 AM" src="https://user-images.githubusercontent.com/86277104/126020883-1380885b-cafd-4469-b353-a056577c9cf8.png"> 
 



