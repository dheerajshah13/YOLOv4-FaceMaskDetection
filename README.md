# YOLOv4-FaceMaskDetection
Object detection models continue to get better, increasing in both performance and speed. In the realtime object detection space, YOLOv3 (released April 8, 2018) has been a popular choice, as has EfficientDet (released April 3rd, 2020) by the Google Brain team. Progress continues with the recent release of YOLOv4 (released April 23rd, 2020), which has been shown to be the new object detection champion by standard metrics on COCO.

!![image-44](https://user-images.githubusercontent.com/52134299/105405811-96f9ed00-5c51-11eb-8fb1-e4d0e800fafd.png)
Source: https://arxiv.org/pdf/2004.10934.pdf
MS COCO Object Detection: Average Precision vs FPS for Efficientnet, YOLOv4, YOLOv3, and ASFF.

These general object detection models are proven out on the COCO dataset which contains a wide range of objects and classes with the idea that if they can perform well on that task, they will generalize well to new datasets. However, applying the deep learning techniques used in research can be difficult in practice on custom objects.

# DATASET
To train YOLOv4 on Darknet with our custom dataset, we need to import our dataset in Darknet YOLO format. To import our images and bounding boxes in the YOLO Darknet format, the Roboflow is used (https://public.roboflow.com)
![Screenshot 2021-01-22 at 1 40 38 AM](https://user-images.githubusercontent.com/52134299/105407101-4e433380-5c53-11eb-9e61-ce70eb8c4896.png)
# Inference
 The trained custom YOLO v4 detector to make inference on test images. When training, the trained weights for the detector are saved every 500 iterations in the ./backup/ directory. We can reload these weights and make inference on a test image. Remember to use the weights that achieved the highest mAP on your validation set.
![Screenshot 2021-01-22 at 1 46 23 AM](https://user-images.githubusercontent.com/52134299/105407386-ae39da00-5c53-11eb-9418-07071ffcef3f.png)

