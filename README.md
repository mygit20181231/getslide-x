# getslide-x
使用YOLO v8获取滑块图像x位置

一、可获得滑块验证图像横坐标位置，运行前需要安装yolo v8

二、根据文件存放情况，更改data/data.yaml文件配置

train: d:/2/data/train  # train images (relative to 'path') 4 images

val: d:/2/data/val  # val images (relative to 'path') 4 images

test: d:/2/data/test  # test images (optional)

三、
train.py  #训练
val.py    #推断，r.boxes.xyxy[0][0]是横坐标


