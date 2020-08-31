# [How to train an object detection model with mmdetection](https://www.dlology.com/blog/how-to-train-an-object-detection-model-with-mmdetection/) | DLology blog

## Quick start
Train an object detection with Google Colab and free GPU.

Train with custom Pascal VOC dataset.
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Tony607/mmdetection_object_detection_demo/blob/master/mmdetection_train_custom_data.ipynb)

Train with custom COCO dataset.
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Tony607/mmdetection_object_detection_demo/blob/master/mmdetection_train_custom_coco_data.ipynb)

*The `data/VOC2007` folder provides a reference structure of custom dataset ready for training. Fork my repository and replace them with your custom annotated dataset as necessary.*


Further instruction on how to create your own datasets, read the tutorials
- [How to train an object detection model with mmdetection](https://www.dlology.com/blog/how-to-train-an-object-detection-model-with-mmdetection/) - Custom Pascal VOC dataset.
- [How to create custom COCO data set for object detection](https://www.dlology.com/blog/how-to-create-custom-coco-data-set-for-object-detection/) - Custom COCO dataset.


To custom train models using mmdetection - 
For training using the Faster RCNN model based on FPN,RetinaNet50 make sure you make the following changes:

Config Changes :
mmdet/dataset/pascal_voc/  in config file : make necessary changes - number of classes,epochs,batch_size and other hyperparameters if required.
