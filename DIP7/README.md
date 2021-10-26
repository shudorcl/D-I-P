# 数字图像处理实验7

任务1

- 请编写代码，通过频域滤波方法，过滤掉stripy_cameraman.png中的条状噪声

- 提示：通过在频域比较cameraman.tif的频谱图像来确定滤掉哪个部分

![stripy_cameraman](https://github.com/shudorcl/D-I-P/blob/main/DIP7/stripy_cameraman.png.png)

任务2

- 将彩色图像'araras.jpg'的RGB 3个通道用灰度图显示出来

![araras](https://github.com/shudorcl/D-I-P/blob/main/DIP7/araras.jpg)

任务3

- 实现彩色图像的直方图均衡化，并用stream.jpg来验证

![stream](https://github.com/shudorcl/D-I-P/blob/main/DIP7/stream.jpg)

## 思路

任务一对比傅里叶幅度谱，然后手动涂黑滤波即可