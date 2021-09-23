# 数字图像处理实验3

实验要求:

- 将wukong.jpg中的内容，通过几何变换贴到board1.jpg和board2.jpg中的某张海报墙上

- 自己选一张图片，重复如上操作

- 要求编程实现，而不是手工处理

![wukong](https://github.com/shudorcl/D-I-P/blob/main/DIP3/wukong.jpg)

![board2](https://github.com/shudorcl/D-I-P/blob/main/DIP3/board2.jpg)

思路：

手动找出海报墙四个点的坐标，以此截取ROI，运用透视变换转化图像，最后仿照上次实验的方法拼合在一起

（参照资料-opencv 4.1中文官方文档中图像上的透视变换一节）

效果：

![result](https://github.com/shudorcl/D-I-P/blob/main/DIP3/result.png)