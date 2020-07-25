# Real-Time-Object-Detection-using-YOLOv3
Peformed real time object detection in videos using YOLO algorithm.
Used Open CV to read the video, frame by frame. Each frame is passed through yolov3 model to detect several objects.
Certain boxes are eliminated on basis on low confidence score.
Used Non-Max Supression to eliminate overlapping boxes which detect the same object.
Drawing finalized boxes with labeled objects while displaying their confidence scores alongside uisng Open CV.
