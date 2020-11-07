# geomagic touch 力反馈设备的驱动及ros包
## 使用命令
/opt/geomagic_touch_device_driver/Geomagic_Touch_Setup   //坑：一个device只能对应一个name，否则第二个命令会出错，用 geomagic的名字来对应设备
/opt/geomagic_touch_device_driver/Geomagic_Touch_Diagnostic
roslaunch geomagic_control geomagic.launch  //打开设备的rviz并且同步位姿，launch里面的device name是连接重要信息，详情阅读该文件注释  
rosrun geomagic_control omni//目前没用，控制机械臂的命令见rosproject readme
## 文件说明
geomagic_touch_device_driver_2016.1-1-amd64   驱动  
openhaptics_3.4-0-developer-edition-amd64   sdk  
geomagic_touch-master   ros包


## issues reference:
https://www.google.com/amp/s/kyliublog.wordpress.com/2018/12/13/geomagic-touch-installation-in-ubuntu-16-04-ros-kinetic/amp/  
https://github.com/inria-larsen/icub-manual/wiki/Installation-with-the-Geomagic-Touch

