# Project3 - Localisation
Localisation of robot

## Follow the following Steps to launch the project 

 * ### Clone the repository
    
    ```git clone https://github.com/manjotsinghsuri/Project-localisation.git```

* ### Then build the packages 

    ```catkin_make```

* ### Then source it
    ```source devel/setup.bash```

* ### Launching the world
    ```roslaunch my_robot my_world```

* ### Launching AMCL launch file with amcl node, move_base node and rviz
    ```roslaunch my_robot amcl.launch```

* ### If u want to move robot my teleopeartion 
    ```rosrun teleop_twist_keyboard simple_teleop.py```

### Now move the robot either using teleoperation or using 2D Navigation Goal feature in RVIZ, u will see robot loacalising in rviz.


