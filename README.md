![](https://github.com/arisrtle/yolo_fire/blob/main/002000.jpg)
![](https://github.com/arisrtle/yolo_fire/blob/main/visualize_002000.jpg)

# YOLO V2 with Jupyter to detect fire phenomena
***
Here is a jupyter notebook featuring a complete implementation from scratch of YOLOV2 with Jupyter :

-Dataset pipeline with data augmentation

-Training from YOLO pretrained weights

-Visualization of object detection

I use this notebook to train a model to detect fire. The goal is to detect fire in real time for safety.

## File

* main.ipynb : Yolo V2 implementation.

## Requirements

* PaddleX 2.0
* cv2
* PIL

## Before using the notebook

* Download the [Fire Dataset](https://aistudio.baidu.com/aistudio/datasetdetail/127785), and put it in the same directory of the .ipynb file.

The pictures examples in this Dataset are shown as follows:

![](https://github.com/arisrtle/yolo_fire/blob/main/datasetExamples.png)

That's it, enjoy your time!

## Credits
Many thanks to these great repositories:

https://github.com/experiencor/keras-yolo2

https://github.com/allanzelener/YAD2K

and to this very good explanation of the YOLO V2 loss function:

https://fairyonice.github.io/Part_4_Object_Detection_with_Yolo_using_VOC_2012_data_loss.html
