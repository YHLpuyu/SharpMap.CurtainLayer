# SharpMap.CurtainLayer
基于sharpmap的卷帘效果

使用方法：
1.创建两个BruTile.ITileSource,分别为左、右视窗显示内容
2.实例化CurtainLayer类
3.调用Add2Map方法添加到地图中
4.移除时，调用RemoveFromMap(),从地图中移除


![效果图](https://github.com/YHLpuyu/SharpMap.CurtainLayer/blob/master/image.png)
鼠标点击中间白色竖线，鼠标变成垂直分割样式，拖动即可更改左右视窗大小
