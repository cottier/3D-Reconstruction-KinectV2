通过三个相机采集：相机参数 干扰下的xef 纯净的深度图 彩色图 强度图

输入从xef（包含串扰）提取出来的深度图，和一张对应的彩色图
通过pcfromkinect得每个深度图对应的点云

TODO:
1/ 从xef提取深度图，对深度图平均
2/ 通过pcfromkinect得每个深度图对应的点云
3/ 双目标定

0/ infrared的extrator
0/ 比较彩色相机和红外相机的标定