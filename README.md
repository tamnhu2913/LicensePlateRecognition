# License Plate Recognition using YOLOv9 and EasyOCR

- This repository contains code and resources for a project aimed at recognizing vehicle license plates using the *YOLOv9* object detection model and *EasyOCR* for optical character recognition (OCR). The project involves detecting license plates in images and extracting the text from the detected plates.

- The dataset is downloaded from *Kaggle*: https://www.kaggle.com/datasets/andrewmvd/car-plate-detection/data. It contains 433 images with bounding box annotations of the license plates within the images.

- The *YOLOv9* model has been customized for this project. For example, the number of classes is set to 1, representing the license plate label. Additionally, some changes made to the hyp.scratch-high.yaml file include lr0: 0.001, lrf: 0.001, iou_t: 0.5, and shear: 0.3.

- *EasyOCR* has been used to detect the text on the license plates based on the bounding box predictions of the YOLOv9 model. The languages used in *EasyOCR* are English and French.
  
- The test image are download from https://www.topreg.co.uk/assets/media/44-golf-reg-1090x670.jpg.



