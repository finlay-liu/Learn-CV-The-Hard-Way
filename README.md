# Learn-CV-The-Hard-Way
Learn Computer Vision The Hard Way，通过实际案例来学习计算机视觉。

## 学习内容

- 常见计算机视觉任务；
- 数字图像基础；
- 卷积神经网络基础；
- Pytorch基础
- 计算机视觉赛题学习；

## 常见的计算视觉任务

1. 图像分类（Image Classification）：给定一张图，对图像物体进行分类；
2. 物体识别（Object Detection）：识别图中每个物体的位置和类别；
3. 语义分割（Semantic Segmentation）：将图中每个像素点进行语义分类；
4. 实例分割（Instance Segmentation）：将图中每个像素点进行实例分类；
5. 人体姿态估计（Pose Estimation）：识别图中每个人的姿态关键点；

更加直观的任务介绍见：https://gluon-cv.mxnet.io/

当然还有很多其他的计算机视觉应用，如人脸关键点检测、人脸识别、视频分类、物体追踪和图像风格转换等，但诸多的应用都可以从如下角度进行总结和学习：

- 任务的**定义**是什么（任务目标和评价指标）？
- 任务常见的**解决方法**是（常见模型）？
- 任务有什么**应用场景**？

## 数字图像基础

- 图像操作与处理
- OpenCV基础
- 图像局部描述算子

## 卷积神经网络基础

- 卷积神经网络基础
  - 基本结构
  - 发展历程
- 卷积神经网络构成
  - 卷积层
  - 激活函数层
  - Pooling层
  - BN层
- 常见的卷积神经网络结构
  - AlexNet
  - VGG
  - ResNet
- 卷积神经网络实践
  - 参数初始化
  - 数据扩增方式
  - 目的函数与优化器
  - 网络正则化

## Pytorch基础

- Pytroch基础
  - Pytorch安装
  - 数据结构Tensor与Variable
  - 自动微分autograd

- 数据DataLoader
  - 内置的Dataset与DataLoader
  - 自定义Dataset
  - 常见的数据扩增方法

- 模型搭建
  - 模型搭建Sequential
  - 常见的网络层
  - 常见的参数初始化方法

- 优化器与损失函数
  - 常见的优化器
  - 常见的损失函数
  - 学习率调整策略
  - EarlyStop等正则化技术

- 模型评价方法
  - 分类Top1与Top5准确率计算
  - 分类AUC计算
  - 分类混淆矩阵计算

- 模型训练与验证
  - 模型训练与验证
  - 模型权重保存与加载
  - 模型单级多卡实验

## 计算机视觉赛题

- [分类]- AI研习社：胸腔X光肺炎检测，[ https://god.yanxishe.com/13](https://god.yanxishe.com/13)

- [分类]- AI研习社：猫狗大战，<https://god.yanxishe.com/8>

- [回归]- AI研习社：人脸年龄识别，[ https://god.yanxishe.com/10](https://god.yanxishe.com/10)

- [物体检测+人脸检测]- AI研习社：安全帽检测，<https://god.yanxishe.com/12>

- [物体检测+OCR]- Tinymind：人民币编码识别，<https://www.tinymind.cn/competitions/47>

 ## 书籍推荐

1. 《动手学习深度学习》

   作者：阿斯顿·张，李沐，扎卡里 C. 立顿和亚历山大 J. 斯莫拉

   介绍：基于MXNET框架的深度学习实战教材，代码、课程和讲义完全开源，适合入门；

   MXNet版：<http://zh.gluon.ai/index.html>

   PyTorch版：<https://github.com/ShusenTang/Dive-into-DL-PyTorch>

2. 《解析深度学习——卷积神经网络原理与视觉实践

   作者：[魏秀参（Xiu-Shen WEI）](http://www.weixiushen.com/)

   介绍：轻量级、偏实用的深度学习工具书，侧重深度卷积神经网络基础和应用；

   开源电子版：http://www.weixiushen.com/book/CNN_book.html

3. 《Python计算机视觉》

   Jan Erik Solem (作者) 朱文涛 , 袁勇 (译者)

   介绍：介绍了Python环境下的图像处理基本操作；
