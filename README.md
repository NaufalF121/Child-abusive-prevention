# Child Abusive Prevention

Model Used :
- coatnet_balance_data (using utk dataset and do undersampling for age estimation)
- coatnet_unbalanced_data (using utk dataset and class not balance for age estimation)
- coatnet_YLFW (Utk + YLFW datasetfor age estimation)
- model_resnet (utk only and not balance for age estimation)
- yolov8n_100e (object detection)
- model_resnet_YLFW (WIP...)

Best combination yolov8s + model_resnet Overall FPS 0-2 fps for realtime prediction</br>

Data used : 
- [UTK](https://www.kaggle.com/datasets/jangedoo/utkface-new)
- [YLFW](https://www.kaggle.com/datasets/swarnava007/ylfw-benchmark)