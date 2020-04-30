# my note

## 目录
- [2020](#2020)
  - [4月](#4月)
    - [23日](#23日)
    - [24日](#24日)
    - [26日](#26日)
    - [27日](#27日)
    - [28日](#28日)
    - [29日](#29日)


## 2020
### 4月
#### 23日
1. 基于amap-shsmi-loader 加载器版本Amap不带权限的地图控件部署到政务网10.108.3.16机器上
2. 修改了基于3x 和4x api 调用的demo
3. 修改了开发者中心smidevelopCenter 中demo示例
4. amap-shsmi-loader更新使用说明，并发布到NPM至0.0.11 版本
5. 徐汇行政服务中心代码区网络和市网络ip修改

#### 24日
1. 专业继续教育了学习考试

#### 26日
1. github 上 amap-shsmi、amap-shsmi-loader、AMapLoader-MapControl、AMap-shsmi-demo工程重名了，统一AMap 改成 SMap. amap-shsmi的四大分支amap-shsmi、amap3x-shsmi、amap-jsapi-shsmi、amap3x-jsapi-shsmi统一重命名成 smap-jsapi-authority-shsmi、smap3x-jsapi-authority-shsmi、smap-jsapi-cofig-shsmi、smap3x-jsapi-cofig-shsmi。

2. npm 上统一以smap-shsmi-loader、smap-shsmi、smap3x-shsmi 发布新包。

3. AMapLoader-MapControl、AMap-shsmi-demo 工程控件和示例地图控件重命名。

4. 政务网10.108.3.16 上 smi 和smidevelopcenter 部署内容更新

5. smap 工程添加了smapbussinessconfig 地图业务图层组配置，便于其它业务图层扩展

6. 添加了addmapcontrol 控件，并实现了smap-web 中添加地图控件测试


#### 27日
1.  SMap中二维、三维地图图层重新配置和图层加载接口开发，实现二三维情况下加载不同的数据
2.  SMap中LayerListControl,Zoom,Home,Compass,Fullscreen,UndergroundSwitch地图控件开发
3.  SMap中LayerListControl,Zoom,Home,Compass,Fullscreen,UndergroundSwitch控件调用示例开发
4.  SMap中LayerListControl,Zoom,Home,Compass,Fullscreen,UndergroundSwitch控件使用说明更新
5.  SMAP工程中的ReadMe.md 使用说明文件更新
6.  SMap包提交到NPM官方网站，实现更新


#### 28日
1.  SMap中MeasureLine,MeasureArea,BasemapToggle地图控件开发
2.  SMAP中MeasureLine,MeasureArea,BasemapToggle对应的ArcGIS Mapview 和SenceView 中的DistanceMeasureMentButton2D,
    DistanceMeasureMentButton3D,AreaMeasureMentButton2D,AreaMeasureMentButton3D,BaseMapSwitchButton2D,
    BaseMapSwitchButton3D地图控件样式开发修改，满足了控件多次加载。
3.  SMap中MeasureLine,MeasureArea,BasemapToggle控件调用示例开发
4.  SMap中MeasureLine,MeasureArea,BasemapToggle控件使用说明更新
5.  SMAP工程中的ReadMe.md 使用说明文件更新
6.  SMap包提交到NPM官方网站，实现更新

#### 29日
1. SMAP中MAP 添加了mapStyle、showBuildingBlock等控制属性，实现地图样式、是否显示建筑物等信息控制
2. MAP中添加setRotation 方法实现地图旋转功能，支持二三维
3. 更新了地图使用说明，添加了地图样式、是否显示建筑物、地图setRotation等使用说明
4. 更新了NPM smap-shsmi包。

#### 30日
1. 徐汇区添加了地下管线数据包括 电信、电力、燃气、给水、排水等三维管线数据，并
开放了地下模式切换接口。
2. SMAP中MAP添加zoomIn、zoomOut、setMapStyle、getMapStyle、setPitch、getPitch等方法。
3. 更新了地图使用说明，添加了zoomIn、zoomOut、setMapStyle、getMapStyle、setPitch、getPitch等使用说明
4. 更新了NPM smap-shsmi包。