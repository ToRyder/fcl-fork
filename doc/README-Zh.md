## FCL -- 灵活的碰撞库

Linux / OS X [![Build Status](https://travis-ci.org/flexible-collision-library/fcl.svg?branch=master)](https://travis-ci.org/flexible-collision-library/fcl)
Windows [![Build status](https://ci.appveyor.com/api/projects/status/do1k727uu6e8uemf/branch/master?svg=true)](https://ci.appveyor.com/project/flexible-collision-library/fcl)
Coverage [![Coverage Status](https://coveralls.io/repos/github/flexible-collision-library/fcl/badge.svg?branch=master)](https://coveralls.io/github/flexible-collision-library/fcl?branch=master)

FCL是一个库，用于对一对由三角形组成的几何模型执行三种类型的邻近查询。
- 碰撞检测：检测两个模型是否重叠，也可以检测重叠的所有三角形。
- 距离计算：计算一对模型之间的最小距离，即最近的一对点之间的距离。
- 公差验证：确定两个模型是否比公差距离更近或更远。
- 连续碰撞检测：检测两个运动模型在运动过程中是否重叠，并可选择检测接触时间。
- 联系信息：对于碰撞检测和连续碰撞检测，可以选择性地返回联系信息（包括接触法线和接触点）。

FCL具有以下特点
- C++接口
- 可用于linux或win32（makefile和Microsoft Visual项目都可以使用cmake生成）
- 输入模型不需要特殊的拓扑约束或邻接信息——所需要的只是模型的三角形列表
- 支持不同的对象形状：
+ 箱子
+ 球体
+ 椭球
+ 胶囊
+ 锥体
+ 圆柱体
+ 凸面
+ 半空间
+ 平面
+ 网格
+ 八叉树（可选，八叉树使用octmap库表示http://octomap.github.com)


## 安装

