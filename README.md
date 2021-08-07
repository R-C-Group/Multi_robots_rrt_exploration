# Multi_robots_rrt_exploration
实现多机器人的RRT-exploration的gazebo仿真,并将机器人探索的路径轨迹通过rviz显示出来 
步骤: 
1.在launch_test.sh文件所在的路径下运行命令：sh launch_test.sh ;
2.在rviz上利用Publish Point 点5个点，其中四个点包含所有的机器人，最后一个点在中间;
3.在rviz上订阅Path/trajectory_odom_rb1,Path/trajectory_odom_rb2,Path/trajectory_odom_rb3;
4.运行rosrun map_server map_saver map:=/map_merge/map -f map命令保存地图.
