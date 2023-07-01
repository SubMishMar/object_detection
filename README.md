# Object detection in an urban environment

## Video Output
[![Comparing Object Detection Across Various Models](https://img.youtube.com/vi/tLTIcaBzBfc/0.jpg)](https://www.youtube.com/watch?v=tLTIcaBzBfc)

## Models Trained (With Config Files)
* [EfficientDet](https://github.com/SubMishMar/object_detection/blob/main/1_model_training/source_dir/pipeline.config)
* [Faster-RCNN ResNet50](https://github.com/SubMishMar/object_detection/blob/main/1_model_training/source_dir/faster_rcnn_resnet50_v1_640x640_coco17_tpu-8.config)
* [SSD-MobileNet-V1-FPN](https://github.com/SubMishMar/object_detection/blob/main/1_model_training/source_dir/ssd_mobilenet_v1_fpn_640x640_coco17_tpu-8.config)
* [SSD-MobileNet-V2-FPNLite](https://github.com/SubMishMar/object_detection/blob/main/1_model_training/source_dir/ssd_mobilenet_v2_fpnlite_640x640_coco17_tpu-8.config)

### EfficientDet
```
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.074
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.183
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.053
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.028
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.279
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.258
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.020
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.086
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.127
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.072
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.409
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.609
```
### Faster-RCNN ResNet50
```
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.121
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.282
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.092
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.049
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.316
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.442
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.029
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.126
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.188
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.108
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.431
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.534
```
### SSD-MobileNet-V1-FPN
```
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.195
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.376
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.174
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.090
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.493
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.611
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.039
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.182
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.276
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.173
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.602
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.703
```
### SSD-MobileNet-V2-FPNLite
```
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.093
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.188
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.084
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.035
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.356
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.470
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.023
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.100
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.156
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.091
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.471
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.541
```
### Discussion
Overall,  `SSD-MobileNet-V1-FPN` performed the best with an `mAP@[IoU=0.50:0.95] = 0.195`.
As far as small objects are considered. again `SSD-MobilNet-V1-FPN` performs the best with `mAP@[IoU=0.50:0.95] = 0.090`.
For large objects, again `SSD-MobilNet-V1-FPN` performs the best with `mAP@[IoU=0.50:0.95] = 0.611`.

All the models were trained for 2000 steps using a momentum optimizer. `Faster-RCNN ResNet50` was the hardest to train so a larger instance had to be employed, the details of which can be found in the relevant [notebook](https://github.com/SubMishMar/object_detection/blob/main/1_model_training/1_train_model_faster_rcnn_resnet50_v1_640x640_coco17_tpu-8.ipynb). The batch size was 8 for all models except for `Faster-RCNN ResNet50` which had a batch size of 4 to be able to be trained in the available compute within reasonable time.

In my opinion, different models would require different solver options, batch sizes, kinds of solvers, to perform the best. However, in the current instance, with the solver parameters kept fixed (except for a different batch size for `FasterRCNN-ResNet50`), `SSD-MobileNet-V1-FPN`, has the best object detection metrics.
