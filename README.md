# RBDcm计算机辅助诊断系统
---
- 简介
  RBDcm计算机辅助诊断系统是用于查看.dcm标准肺部CT影像，并辅助自动检测肺结节的一套软件。软件运行于Windows7操作系统。

## 依赖
- DCMTK3.6.1开源软件
- OpenCV2.4.11计算机视觉开源软件

## 支持功能

1. 序列图像打开，从横断面图像重建得到冠状面和矢状面图像。 
2. 点击横断面图像显示相应定位线到冠状面和矢状面。
3. 输入训练文件，识别分割后图像中的肺结节。
4. 图像灰度直方图显示。
5. 图像序列播放。
6. 可选多种图像分割方式。
7. 可选多种图像增强方式。

## 工作站界面：
使用SVM分类器对横断面进行结节检测结果：
<center>
![image](https://github.com/bzhou830/images/raw/master/2015.png)
</center>
横断面，矢状面，冠状面三剖面下结节：
<center>
![image](https://github.com/bzhou830/images/raw/master/face.png)
</center>


##联系作者
E-mail: bzhou830@qq.com


##License
RBDcm计算机辅助诊断系统的代码使用MIT License发布，此外，禁止使用RBDcm计算机辅助诊断系统以及RBDcm计算机辅助诊断系统的修改程序用于任何商业目的。
