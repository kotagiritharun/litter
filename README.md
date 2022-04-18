# litter
littering on roads
The algorithm can distinguish PET, plastic, light_bulb, paper and cardboard garbages. It had 16 FPS in average on a Tesla P100-PCI-E-16GB

Project steps
Record the video
Create a custom dataset by annotating 50 frames with CVAT
Train yolov4 on the small dataset
Generate pseudo labels with the trained model
Import, and fix the generated iamges manually in CVAT
Retrain the model on the larger dataset
Process the video
Tested models
yolov4 Results: https://www.youtube.com/watch?v=iumbdbNbZsM
 EfficientDet D0
 yolov3
