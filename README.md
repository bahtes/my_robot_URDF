URDF files for a simple robot that can be simulated in RVis

I had a few issues running the robot_state_publisher with the xacro files so I used `xacro filename.urdf.xacro > newfilename.urdf` where filename.urdf.xacro is the main xacro file and newfile.urdf is a new urdf file that will be runnable with robot_state_publisher by using the command `ros2 run robot_state_publisher robot_state_publisher newfile.urdf`
This has already been done in this repo, to run this project you will need ros2.

To run start with the command `ros2 run robot_state_publisher robot_state_publisher newfile.urdf`.  Then run the command `ros2 run joint_state_publisher_gui joint_state_publisher_gui`.  And then run RViz2 with the command `RViz2`

I may update this with launch files so it can be ran easier.
