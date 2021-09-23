# 数字图像处理实验2

实验要求：

- 将cat.jpg中猫放置到table.jpg中的桌子上

- 要求编程实现，而不是手工处理

![cat](https://github.com/shudorcl/D-I-P/blob/main/DIP2/cat.jpg)

![table](https://github.com/shudorcl/D-I-P/blob/main/DIP2/table.jpg)

思路：

按照颜色区域生成掩膜，而后运用按位和运算合成ROI区域的图像，加入到原图中

（参照资料-opencv 4.1中文官方文档中图像上的算术运算一节）

效果：

![catable_hsv](https://github.com/shudorcl/D-I-P/blob/main/DIP2/catontable_hsv.png)


