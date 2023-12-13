This package is used for utilizing the keep-out zone for the navigation using ROS2. This part of the place will not be considered for doing the navigation. It will be useful in industrial settings where certain area are having restricted movements.



![Screenshot from 2023-12-13 14-54-01](https://github.com/sreesms/nav2_keepout_filter/assets/19260407/de4058cb-9032-460d-bab9-c8300334b96f)


After edit in GIMP, we can make as follow.

![Screenshot from 2023-12-13 15-20-51](https://github.com/sreesms/nav2_keepout_filter/assets/19260407/67f25e76-44c7-4d0d-83a6-80ed61bd889f)


The keepout parameter(keepout_params.yaml)

![Screenshot from 2023-12-13 17-18-23](https://github.com/sreesms/nav2_keepout_filter/assets/19260407/46b91c96-5ec1-41e7-8336-50a5619aaef8)


For more details refer the following documentation:

https://navigation.ros.org/tutorials/docs/navigation2_with_keepout_filter.html



# Method of Running the packages

## ros2 launch nav2_costmap_filters_demo costmap_filter_info.launch.py
## ros2 launch nav2_bringup tb3_simulation_launch.py headless:=False
![Screenshot from 2023-12-13 17-27-41](https://github.com/sreesms/nav2_keepout_filter/assets/19260407/caffdb30-22d4-43a9-9ca9-7c0a807f2147)


![Screenshot from 2023-12-13 15-29-36](https://github.com/sreesms/nav2_keepout_filter/assets/19260407/530320d0-51d4-442f-bc35-c47f23f22e2b)
