# orcvio_mapping



- Download rosbag: [darknet_sort-ros_2021-04-11-19-46-21.bag](https://drive.google.com/file/d/1TTjIp5nEb-oXvUbZAXSynJOJO2AjCekt/view?usp=sharing)

- Run

```
roslaunch orcvio_mapping orcvio_object_mapping_dcist.launch rosbag_path:=/Download Folder/darknet_sort-ros_2021-04-11-19-46-21.bag
```

* Parameters

  * min_dist_btw_objects: minimum distance between two objects.

  * max_dist_btw_cam_obj: maximum distance between the first viewpoint and object.

    

* Other resources

  Raw rosbag (without tracking) from MIT: [link]( https://www.dropbox.com/sh/bovb04lrb0l745r/AAA69peH_ELWLNzvkTwoeRB4a?dl=0&lst=&preview=indoor_vio5_2020-11-03-18-44-15.bag)

  More raw rosbags MIT: [link](https://www.dropbox.com/sh/bovb04lrb0l745r/AAA69peH_ELWLNzvkTwoeRB4a?dl=0)