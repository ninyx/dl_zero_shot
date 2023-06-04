# A series of Zero SHot Projects for Deep Learning 
### Project 1: Implementation of a zero-shot object detection with Meta AI's Segment Anything Model (SAM) and MLFoundation's OpenCLIP.
  - For this project, Segment Anything Model was used to identify bounding boxes of objects in images 
  - Using the 80 categories from the COCO dataset, I created a prompt to be tokenized and used to identify the images in OpenCLIP.
  - Results are compared with YOLOv8 and are displayed side by side 
  - COCO 2017 validation set was used for mAP calcultaion
  - Image import is supported through path or url.

### Project 2: Implementation of a zero-shot keyword spotting using Meta AI's ImageBind
  - For this project, I used the KWS test split for validation using ImageBind
  - Audio recording and file uploads are supported, though results are not as accurate
  - Working project, aforementioned features will be added later on
