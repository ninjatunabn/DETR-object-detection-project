# tusul-num
detr


#Төслийн ажил/DETR

Dataset
- prepared my dataset of basketball ball in roboflow
- it is free, open-source dataset preperation web
- dataset format - COCO

Training code
- google colab has gpu that is why i used it
- configs:
  -annotations folder in dataset folder /instances_train2017.json, instances_test2017.json, isntances_val2017.json/
  - train2017, val2017, test2017 folders
  - number of classes in /models/detr.py

Detect with usb webcam
  - used camera:

Here is the code in colab 
https://colab.research.google.com/drive/1TvkwP_5P4XZeXdHJJRAwAUTdfBaqBbZN?usp=drive_link
