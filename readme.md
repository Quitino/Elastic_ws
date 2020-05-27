##  0.ElasticFusion

使用realsense D435i相机运行。如有帮助到您，点个赞啊.

![test pic](./test.png)

- [test video](https://www.youtube.com/watch?v=lZbeH9t7DzQ&feature=youtu.be)

## 1.install



- [安装参考0.ElasticFusion编译过程（Ubuntu16.04）](https://blog.csdn.net/jthree2012/article/details/80837661)
- [安装参考1.Ubuntu18.04+realsense运行ElasticFusion](https://blog.csdn.net/dongzid/article/details/85906109)
- [安装参考2.Ubuntu16.04+realsense运行ElasticFusion](https://blog.csdn.net/u010497704/article/details/89490675)



##  2.run

```bash
source devel/setup.bash
roslaunch elastic_bridge ElasticFusionRealsense.launch
```

笔记本跑的，性能不够，跑到后面就会卡死。

- [test video](https://www.youtube.com/watch?v=lZbeH9t7DzQ&feature=youtu.be)


##  3.TODO

和这个库无关，备忘一下，使用VINS-Fusion进行轨迹估计，rtab-map建图，相机选用D435i，支持回环检测更新地图.待测试。

- [ref0](http://official-rtab-map-forum.67519.x6.nabble.com/RTAB-map-with-vins-Fusion-td6111.html)
- [ref1](https://my.oschina.net/u/4377611/blog/3564539)
