# YOLOV5_OpenCV_Task
In this task, I used the YOLOV5 model to use in  object detection on image.

https://github.com/ultralytics/yolov5

I used the yolov5 repository to download pretrained model.
https://github.com/ultralytics/yolov5/releases/download/v7.0/yolov5m.pt


First I used pretrained YOLOV5m model, and then I exported it to the ONNX model with the yolov5 repository to use it in OpenCV with the below command.

python3 export.py --weights yolov5m.pt --include onnx


to use it in OpenCV.After exporting the model run simple object detection with Python and CPP on phone images.
