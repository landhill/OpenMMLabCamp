训练模型的配置文件【mask_rcnn_r50_caffe_fpn_mstrain-poly_1x_balloon.py】

训练好的模型文件【best_bbox_mAP_epoch_77.pth】（百度网盘链接: https://pan.baidu.com/s/1o2izJ7QAfaSF-LHAvLKXuw?pwd=uih2 提取码: uih2 ）

```shell
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.771
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=1000 ] = 0.880
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=1000 ] = 0.848
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=1000 ] = 0.151
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=1000 ] = 0.656
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=1000 ] = 0.839
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.828
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=300 ] = 0.828
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=1000 ] = 0.828
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=1000 ] = 0.300
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=1000 ] = 0.758
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=1000 ] = 0.881

Exp name: mask_rcnn_r50_caffe_fpn_mstrain-poly_1x_balloon.py
Epoch(val) [100][13]   bbox_mAP: 0.7713, bbox_mAP_50: 0.8805, bbox_mAP_75: 0.8477, bbox_mAP_s: 0.1515, bbox_mAP_m: 0.6557, bbox_mAP_l: 0.8393, bbox_mAP_copypaste: 0.7713 0.8805 0.8477 
0.1515 0.6557 0.8393
```
视频处理后文件：result.mp4