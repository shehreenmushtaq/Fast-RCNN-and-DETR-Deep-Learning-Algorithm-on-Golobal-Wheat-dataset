# Fast-RCNN-and-DETR-Deep-Learning-Algorithm-on-Golobal-Wheat-dataset

Overview and Summary
In this notebook, Faster R-CNN and DETR is implemneted on the wheat dataset. The dataset has been imported from: global-wheat datasets on Kaggle: https://www.kaggle.com/c/global-wheat-detection/data?select=train

Objective:

The objective is to evaluate different object detection models, including Faster R-CNN and DETR, using the global-wheat dataset on Kaggle. The evaluation metric used will be mean average precision (mAP) at different intersection over union (IoU) thresholds.

Summary:

The task involves comparing different object detection models, including Faster R-CNN, and DETR, using the global-wheat dataset on Kaggle. The goal is to determine which model performs best on this dataset using the mAP metric. Faster R-CNN is a more accurate region-based algorithm that is slower while DETR uses a transformer architecture for object detection. The mAP metric will be used to evaluate the performance of these models. A comparison is made to check which model perform better.

Language, Tools and Libraries: Python, Colab, Kaggle, Jupyter Notebook, Pytorch, Panda, tensorflow

Steps:

Downloading and preprocessing the global-wheat dataset on Kaggle.
Train and validate Faster R-CNN, and DETR models on the dataset using appropriate training parameters and hyperparameters.
Using the trained models to detect objects in the test dataset and generate bounding boxes and class labels.
Calculate mAP at different IoU thresholds for each model.
Comparing the mAP scores for each model to determine which one performs best on the global-wheat dataset.
Analyzing the results and identify areas for improvement, such as adjusting hyperparameters or using different models.
