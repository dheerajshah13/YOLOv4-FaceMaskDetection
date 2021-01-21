# YOLOv4-FaceMaskDetection
Object detection models continue to get better, increasing in both performance and speed. In the realtime object detection space, YOLOv3 (released April 8, 2018) has been a popular choice, as has EfficientDet (released April 3rd, 2020) by the Google Brain team. Progress continues with the recent release of YOLOv4 (released April 23rd, 2020), which has been shown to be the new object detection champion by standard metrics on COCO.

!![image-44](https://user-images.githubusercontent.com/52134299/105405811-96f9ed00-5c51-11eb-8fb1-e4d0e800fafd.png)

MS COCO Object Detection: Average Precision vs FPS for Efficientnet, YOLOv4, YOLOv3, and ASFF.
YOLOv4 performance from the paper. (Citation)
These general object detection models are proven out on the COCO dataset which contains a wide range of objects and classes with the idea that if they can perform well on that task, they will generalize well to new datasets. However, applying the deep learning techniques used in research can be difficult in practice on custom objects. We have been working to make that transition easy and have released similar tutorials in the past including:
