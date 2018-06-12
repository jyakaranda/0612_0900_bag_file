- [bag 文件说明](#bag)
  - [1. 0612_0900_all.bag](#1-0612-0900-allbag)
  - [2. 0612_0900_all_1.bag](#2-0612-0900-all-1bag)
  - [3. 0612_0900_all_2.bag](#3-0612-0900-all-2bag)
  - [4. 0612_0900_all_3.bag](#4-0612-0900-all-3bag)
  - [5. 0612_0900_all_4.bag](#5-0612-0900-all-4bag)
  - [6. 0612_0900_all_5.bag](#6-0612-0900-all-5bag)
  - [7. 0612_0900_all_6.bag](#7-0612-0900-all-6bag)
  - [8. 0612_0900_all_8.bag](#8-0612-0900-all-8bag)
  - [9. 0612_0900_all_9.bag](#9-0612-0900-all-9bag)
- [summary](#summary)


> 录数据命令：
```

roslaunch xrobot_test rosbag_record.launch

rosbag record --output-name=0612_0900_all --buffsize=0 /zed/left/image_raw_color/compressed /zed/left/camera_info /zed/right/image_raw_color/compressed /zed/right/camera_info /zed/odom /tf /tf_static /cv_camera/image_raw /cv_camera/camera_info /lslidar_point_cloud

```

## bag 文件说明

### 1. 0612_0900_all.bag

> status: OK

> usage: 
```
rosbag play --clock 0612_0900_all.bag

rosrun image_transport republish compressed in:=/zed/left/image_raw_color raw out:=/zed/left/image_raw_color

rosrun image_transport republish compressed in:=/zed/right/image_raw_color raw out:=/zed/right/image_raw_color

rosrun rviz rviz -d ~/workspace/catkin_ws/rviz/rosbag_record.rviz
```

> description: 
```
path:        0612_0900_all.bag
version:     2.0
duration:    5:45s (345s)
start:       Jun 12 2018 09:06:09.96 (1528765569.96)
end:         Jun 12 2018 09:11:55.48 (1528765915.48)
size:        13.5 GB
messages:    64075
compression: none [12165/12165 chunks]
types:       nav_msgs/Odometry           [cd5e73d190d741a2f92e81eda573aca7]
             sensor_msgs/CameraInfo      [c9a58c1b0b154e0e6da7578cb991d214]
             sensor_msgs/CompressedImage [8f7a12909da2c9d3332d540a0977563f]
             sensor_msgs/Image           [060021388200f6f0f447d0fcd9c64743]
             sensor_msgs/PointCloud2     [1158d486dd51d683ce2f1be655c3c181]
             tf2_msgs/TFMessage          [94810edda583a504dfda3829e70d7eec]
topics:      /cv_camera/camera_info                  10366 msgs    : sensor_msgs/CameraInfo     
             /cv_camera/image_raw                    10366 msgs    : sensor_msgs/Image          
             /lslidar_point_cloud                     1798 msgs    : sensor_msgs/PointCloud2    
             /tf                                     10386 msgs    : tf2_msgs/TFMessage         
             /tf_static                                  1 msg     : tf2_msgs/TFMessage         
             /zed/left/image_raw_color/compressed    10386 msgs    : sensor_msgs/CompressedImage
             /zed/odom                               10386 msgs    : nav_msgs/Odometry          
             /zed/right/image_raw_color/compressed   10386 msgs    : sensor_msgs/CompressedImage
```

### 2. 0612_0900_all_1.bag

> status: OK

> usage: 
```
rosbag play --clock 0612_0900_all_1.bag

rosrun image_transport republish compressed in:=/zed/left/image_raw_color raw out:=/zed/left/image_raw_color

rosrun image_transport republish compressed in:=/zed/right/image_raw_color raw out:=/zed/right/image_raw_color

rosrun rviz rviz -d ~/workspace/catkin_ws/rviz/rosbag_record.rviz
```

> description: 
```
path:        0612_0900_all_1.bag
version:     2.0
duration:    6:38s (398s)
start:       Jun 12 2018 09:13:30.55 (1528766010.55)
end:         Jun 12 2018 09:20:09.53 (1528766409.53)
size:        14.3 GB
messages:    75044
compression: none [13930/13930 chunks]
types:       nav_msgs/Odometry           [cd5e73d190d741a2f92e81eda573aca7]
             sensor_msgs/CameraInfo      [c9a58c1b0b154e0e6da7578cb991d214]
             sensor_msgs/CompressedImage [8f7a12909da2c9d3332d540a0977563f]
             sensor_msgs/Image           [060021388200f6f0f447d0fcd9c64743]
             sensor_msgs/PointCloud2     [1158d486dd51d683ce2f1be655c3c181]
             tf2_msgs/TFMessage          [94810edda583a504dfda3829e70d7eec]
topics:      /cv_camera/camera_info                  11969 msgs    : sensor_msgs/CameraInfo     
             /cv_camera/image_raw                    11969 msgs    : sensor_msgs/Image          
             /lslidar_point_cloud                     2073 msgs    : sensor_msgs/PointCloud2    
             /tf                                     12259 msgs    : tf2_msgs/TFMessage         
             /tf_static                                  1 msg     : tf2_msgs/TFMessage         
             /zed/left/image_raw_color/compressed    12258 msgs    : sensor_msgs/CompressedImage
             /zed/odom                               12257 msgs    : nav_msgs/Odometry          
             /zed/right/image_raw_color/compressed   12258 msgs    : sensor_msgs/CompressedImage
```

### 3. 0612_0900_all_2.bag

> status: OK

> usage: 
```
rosbag play --clock 0612_0900_all_2.bag

rosrun image_transport republish compressed in:=/zed/left/image_raw_color raw out:=/zed/left/image_raw_color

rosrun image_transport republish compressed in:=/zed/right/image_raw_color raw out:=/zed/right/image_raw_color

rosrun rviz rviz -d ~/workspace/catkin_ws/rviz/rosbag_record.rviz
```

> description: 
```
path:        0612_0900_all_2.bag
version:     2.0
duration:    6:02s (362s)
start:       Jun 12 2018 09:20:29.63 (1528766429.63)
end:         Jun 12 2018 09:26:31.64 (1528766791.64)
size:        13.2 GB
messages:    68278
compression: none [12684/12684 chunks]
types:       nav_msgs/Odometry           [cd5e73d190d741a2f92e81eda573aca7]
             sensor_msgs/CameraInfo      [c9a58c1b0b154e0e6da7578cb991d214]
             sensor_msgs/CompressedImage [8f7a12909da2c9d3332d540a0977563f]
             sensor_msgs/Image           [060021388200f6f0f447d0fcd9c64743]
             sensor_msgs/PointCloud2     [1158d486dd51d683ce2f1be655c3c181]
             tf2_msgs/TFMessage          [94810edda583a504dfda3829e70d7eec]
topics:      /cv_camera/camera_info                  10861 msgs    : sensor_msgs/CameraInfo     
             /cv_camera/image_raw                    10861 msgs    : sensor_msgs/Image          
             /lslidar_point_cloud                     1847 msgs    : sensor_msgs/PointCloud2    
             /tf                                     11177 msgs    : tf2_msgs/TFMessage         
             /tf_static                                  1 msg     : tf2_msgs/TFMessage         
             /zed/left/image_raw_color/compressed    11178 msgs    : sensor_msgs/CompressedImage
             /zed/odom                               11176 msgs    : nav_msgs/Odometry          
             /zed/right/image_raw_color/compressed   11177 msgs    : sensor_msgs/CompressedImage
```

### 4. 0612_0900_all_3.bag

> status: OK

> usage: 
```
rosbag play --clock 0612_0900_all_3.bag

rosrun image_transport republish compressed in:=/zed/left/image_raw_color raw out:=/zed/left/image_raw_color

rosrun image_transport republish compressed in:=/zed/right/image_raw_color raw out:=/zed/right/image_raw_color

rosrun rviz rviz -d ~/workspace/catkin_ws/rviz/rosbag_record.rviz
```

> description: 
```
path:        0612_0900_all_3.bag
version:     2.0
duration:    1:30s (90s)
start:       Jun 12 2018 09:27:31.31 (1528766851.31)
end:         Jun 12 2018 09:29:01.62 (1528766941.62)
size:        3.3 GB
messages:    15912
compression: none [3163/3163 chunks]
types:       nav_msgs/Odometry           [cd5e73d190d741a2f92e81eda573aca7]
             sensor_msgs/CameraInfo      [c9a58c1b0b154e0e6da7578cb991d214]
             sensor_msgs/CompressedImage [8f7a12909da2c9d3332d540a0977563f]
             sensor_msgs/Image           [060021388200f6f0f447d0fcd9c64743]
             sensor_msgs/PointCloud2     [1158d486dd51d683ce2f1be655c3c181]
             tf2_msgs/TFMessage          [94810edda583a504dfda3829e70d7eec]
topics:      /cv_camera/camera_info                  2709 msgs    : sensor_msgs/CameraInfo     
             /cv_camera/image_raw                    2709 msgs    : sensor_msgs/Image          
             /lslidar_point_cloud                     453 msgs    : sensor_msgs/PointCloud2    
             /tf                                     2510 msgs    : tf2_msgs/TFMessage         
             /tf_static                                 1 msg     : tf2_msgs/TFMessage         
             /zed/left/image_raw_color/compressed    2511 msgs    : sensor_msgs/CompressedImage
             /zed/odom                               2509 msgs    : nav_msgs/Odometry          
             /zed/right/image_raw_color/compressed   2510 msgs    : sensor_msgs/CompressedImage
```

### 5. 0612_0900_all_4.bag

> status: lidar OK, zed distorted (usb error)

> usage: 
```
rosbag play --clock 0612_0900_all_4.bag

rosrun image_transport republish compressed in:=/zed/left/image_raw_color raw out:=/zed/left/image_raw_color

rosrun image_transport republish compressed in:=/zed/right/image_raw_color raw out:=/zed/right/image_raw_color

rosrun rviz rviz -d ~/workspace/catkin_ws/rviz/rosbag_record.rviz
```

> description: 
```
path:        0612_0900_all_4.bag
version:     2.0
duration:    1:05s (65s)
start:       Jun 12 2018 09:29:17.46 (1528766957.46)
end:         Jun 12 2018 09:30:22.56 (1528767022.56)
size:        614.6 MB
messages:    6488
compression: none [578/578 chunks]
types:       nav_msgs/Odometry           [cd5e73d190d741a2f92e81eda573aca7]
             sensor_msgs/CompressedImage [8f7a12909da2c9d3332d540a0977563f]
             sensor_msgs/PointCloud2     [1158d486dd51d683ce2f1be655c3c181]
             tf2_msgs/TFMessage          [94810edda583a504dfda3829e70d7eec]
topics:      /lslidar_point_cloud                     327 msgs    : sensor_msgs/PointCloud2    
             /tf                                     1540 msgs    : tf2_msgs/TFMessage         
             /tf_static                                 1 msg     : tf2_msgs/TFMessage         
             /zed/left/image_raw_color/compressed    1540 msgs    : sensor_msgs/CompressedImage
             /zed/odom                               1540 msgs    : nav_msgs/Odometry          
             /zed/right/image_raw_color/compressed   1540 msgs    : sensor_msgs/CompressedImage

```

### 6. 0612_0900_all_5.bag

> status: lidar OK, zed distorted (usb error)

> usage: 
```
rosbag play --clock 0612_0900_all_5.bag

rosrun image_transport republish compressed in:=/zed/left/image_raw_color raw out:=/zed/left/image_raw_color

rosrun image_transport republish compressed in:=/zed/right/image_raw_color raw out:=/zed/right/image_raw_color

rosrun rviz rviz -d ~/workspace/catkin_ws/rviz/rosbag_record.rviz
```

> description: 
```
path:        0612_0900_all_5.bag
version:     2.0
duration:    3:52s (232s)
start:       Jun 12 2018 09:34:11.36 (1528767251.36)
end:         Jun 12 2018 09:38:04.25 (1528767484.25)
size:        1.8 GB
messages:    20566
compression: none [1818/1818 chunks]
types:       nav_msgs/Odometry           [cd5e73d190d741a2f92e81eda573aca7]
             sensor_msgs/CompressedImage [8f7a12909da2c9d3332d540a0977563f]
             sensor_msgs/PointCloud2     [1158d486dd51d683ce2f1be655c3c181]
             tf2_msgs/TFMessage          [94810edda583a504dfda3829e70d7eec]
topics:      /lslidar_point_cloud                    1165 msgs    : sensor_msgs/PointCloud2    
             /tf                                     4850 msgs    : tf2_msgs/TFMessage         
             /tf_static                                 1 msg     : tf2_msgs/TFMessage         
             /zed/left/image_raw_color/compressed    4850 msgs    : sensor_msgs/CompressedImage
             /zed/odom                               4850 msgs    : nav_msgs/Odometry          
             /zed/right/image_raw_color/compressed   4850 msgs    : sensor_msgs/CompressedImage
```

### 7. 0612_0900_all_6.bag

> status: OK

> usage: 
```
rosbag play --clock 0612_0900_all_6.bag

rosrun image_transport republish compressed in:=/zed/left/image_raw_color raw out:=/zed/left/image_raw_color

rosrun image_transport republish compressed in:=/zed/right/image_raw_color raw out:=/zed/right/image_raw_color

rosrun rviz rviz -d ~/workspace/catkin_ws/rviz/rosbag_record.rviz
```

> description: 
```
path:        0612_0900_all_6.bag
version:     2.0
duration:    10:15s (615s)
start:       Jun 12 2018 09:38:11.58 (1528767491.58)
end:         Jun 12 2018 09:48:26.90 (1528768106.90)
size:        6.0 GB
messages:    79287
compression: none [6226/6226 chunks]
types:       nav_msgs/Odometry           [cd5e73d190d741a2f92e81eda573aca7]
             sensor_msgs/CompressedImage [8f7a12909da2c9d3332d540a0977563f]
             sensor_msgs/PointCloud2     [1158d486dd51d683ce2f1be655c3c181]
             tf2_msgs/TFMessage          [94810edda583a504dfda3829e70d7eec]
topics:      /lslidar_point_cloud                     2766 msgs    : sensor_msgs/PointCloud2    
             /tf                                     19130 msgs    : tf2_msgs/TFMessage         
             /tf_static                                  1 msg     : tf2_msgs/TFMessage         
             /zed/left/image_raw_color/compressed    19130 msgs    : sensor_msgs/CompressedImage
             /zed/odom                               19130 msgs    : nav_msgs/Odometry          
             /zed/right/image_raw_color/compressed   19130 msgs    : sensor_msgs/CompressedImage
```

### 8. 0612_0900_all_8.bag

> status: OK

> usage: 
```
rosbag play --clock 0612_0900_all_8.bag

rosrun image_transport republish compressed in:=/zed/left/image_raw_color raw out:=/zed/left/image_raw_color

rosrun image_transport republish compressed in:=/zed/right/image_raw_color raw out:=/zed/right/image_raw_color

rosrun rviz rviz -d ~/workspace/catkin_ws/rviz/rosbag_record.rviz
```

> description: 
```
path:        0612_0900_all_8.bag
version:     2.0
duration:    17:09s (1029s)
start:       Jun 12 2018 09:55:56.06 (1528768556.06)
end:         Jun 12 2018 10:13:05.21 (1528769585.21)
size:        11.2 GB
messages:    131655
compression: none [10285/10285 chunks]
types:       nav_msgs/Odometry           [cd5e73d190d741a2f92e81eda573aca7]
             sensor_msgs/CompressedImage [8f7a12909da2c9d3332d540a0977563f]
             sensor_msgs/PointCloud2     [1158d486dd51d683ce2f1be655c3c181]
             tf2_msgs/TFMessage          [94810edda583a504dfda3829e70d7eec]
topics:      /lslidar_point_cloud                     5141 msgs    : sensor_msgs/PointCloud2    
             /tf                                     31629 msgs    : tf2_msgs/TFMessage         
             /tf_static                                  1 msg     : tf2_msgs/TFMessage         
             /zed/left/image_raw_color/compressed    31629 msgs    : sensor_msgs/CompressedImage
             /zed/odom                               31627 msgs    : nav_msgs/Odometry          
             /zed/right/image_raw_color/compressed   31628 msgs    : sensor_msgs/CompressedImage
```

### 9. 0612_0900_all_9.bag

> status: OK

> usage: 
```
rosbag play --clock 0612_0900_all_9.bag

rosrun image_transport republish compressed in:=/zed/left/image_raw_color raw out:=/zed/left/image_raw_color

rosrun image_transport republish compressed in:=/zed/right/image_raw_color raw out:=/zed/right/image_raw_color

rosrun rviz rviz -d ~/workspace/catkin_ws/rviz/rosbag_record.rviz
```

> description: 
```
path:        0612_0900_all_9.bag
version:     2.0
duration:    13:41s (821s)
start:       Jun 12 2018 10:13:14.17 (1528769594.17)
end:         Jun 12 2018 10:26:55.77 (1528770415.77)
size:        8.8 GB
messages:    102904
compression: none [8767/8767 chunks]
types:       nav_msgs/Odometry           [cd5e73d190d741a2f92e81eda573aca7]
             sensor_msgs/CompressedImage [8f7a12909da2c9d3332d540a0977563f]
             sensor_msgs/PointCloud2     [1158d486dd51d683ce2f1be655c3c181]
             tf2_msgs/TFMessage          [94810edda583a504dfda3829e70d7eec]
topics:      /lslidar_point_cloud                     4103 msgs    : sensor_msgs/PointCloud2    
             /tf                                     24700 msgs    : tf2_msgs/TFMessage         
             /tf_static                                  1 msg     : tf2_msgs/TFMessage         
             /zed/left/image_raw_color/compressed    24700 msgs    : sensor_msgs/CompressedImage
             /zed/odom                               24700 msgs    : nav_msgs/Odometry          
             /zed/right/image_raw_color/compressed   24700 msgs    : sensor_msgs/CompressedImage
```

## summary

- sum : `3957 s`
- lidar : 约 `3957 s`
- zed : 约 `3957 s` (`297 s` zed distorted within all_4.bag and all_5.bag)
- camera : 约 `1195 s` (all_3.bag last `70 s` camera fell)
