# KinectIR
## 环境配置
* opencv2.4.9
* vs2013
* KinectSDK2.0
## 注释
可见此段代码于[之前的项目](https://github.com/TastSong/KinectColor) 几乎一样，只是输出数据时换个函数就行了，Mat开16位是因为`CopyFrameDataToArray()`
中第2个参数指定16位，因此这样的推论应该是正确的。
