# Record Self Learn About Autoware Project - 20200914

## start and goal pose
* use `2D Pose Estimate` in rviz to publish a initial pose, and the topic name is `/initialpose`.
* use `2D Nav Goal` in rviz to publish a goal pose, and the topic name is `/move_base_simple/goal`.

## dynamic objects
* you can add dynamic objects of pedestrian and vehicle to verify your planning and control model.

## Map
* 主流地图格式及框架
> 1. OpenStreetMap(OSM)
> 2. OpenDRIVE
> 3. 各种商用自定义格式

* `autoware`使用`lanelet`地图框架工具  
[参考1](http://www.xchu.net/2020/02/25/42lanelet2-codeparsing/)  
[参考2](http://www.xchu.net/2020/02/24/41lanelet2/)
[参考3](https://blog.csdn.net/orange_littlegirl/article/details/106542743#2lanelet2_5)
> 1. `map_loader node` 加载`osm(Open Street Map)`格式的地图数据.

