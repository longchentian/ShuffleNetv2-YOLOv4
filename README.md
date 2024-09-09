# yolov4-lite-pytorch

## 介绍
yolov4-lite-pytorch

## 软件架构
软件架构说明
该工程主干是来自csdn的[Bubbliiiing](https://blog.csdn.net/weixin_44791964?spm=1001.2014.3001.5509)的github工程
[mobilenet-yolov4-pytorch](https://github.com/bubbliiiing/mobilenet-yolov4-pytorch)

具体操作步骤请转移到该工程哈（这里工程仅仅加入了shufflenetv2的骨干）

## 性能情况
| 训练数据集 | 权值文件名称 | 测试数据集 | 输入图片大小 | mAP 0.5:0.95 | mAP 0.5 |
| :-----: | :-----: | :------: | :------: | :------: | :-----: |
| VOC07+12 | [yolov4_mobilenet_v1_voc.pth](https://github.com/bubbliiiing/mobilenet-yolov4-lite-pytorch/releases/download/v1.0/yolov4_mobilenet_v1_voc.pth) | VOC-Test07 | 416x416 | - | 79.72
| VOC07+12 | [yolov4_mobilenet_v2_voc.pth](https://github.com/bubbliiiing/mobilenet-yolov4-lite-pytorch/releases/download/v1.0/yolov4_mobilenet_v2_voc.pth) | VOC-Test07 | 416x416 | - | 80.12
| VOC07+12 | [yolov4_mobilenet_v3_voc.pth](https://github.com/bubbliiiing/mobilenet-yolov4-lite-pytorch/releases/download/v1.0/yolov4_mobilenet_v3_voc.pth) | VOC-Test07 | 416x416 | - | 79.01
| VOC07+12 | [yolov4_ghostnet_voc.pth](https://github.com/bubbliiiing/mobilenet-yolov4-lite-pytorch/releases/download/v1.0/yolov4_ghostnet_voc.pth) | VOC-Test07 | 416x416 | - | 78.69
| VOC07+12 | [yolov4_densenet121_voc.pth](https://github.com/bubbliiiing/mobilenet-yolov4-lite-pytorch/releases/download/v1.0/yolov4_densenet121_voc.pth) | VOC-Test07 | 416x416 | - | 83.99
| VOC07+12 | [yolov4_shufflenet_v2.pth](https://pan.baidu.com/s/1bFT9y9mGeTrnTRJkv9d0QA) | VOC-Test07 | 416x416 | - | 79.72

权值链接以及提取码
链接：https://pan.baidu.com/s/1bFT9y9mGeTrnTRJkv9d0QA 
提取码：ef6g

## Reference

https://github.com/bubbliiiing/mobilenet-yolov4-pytorch