## 01 - Python's `pathlib` module
 
The pathlib module in Python provides an elegant interface for working with file system paths. The pathlib module offers many advantages over the older os.path way, such as a consistent way to handle paths across different operating systems. The pathlib module does this by treating paths as objects rather than strings. The module also provides methods for common file operations, making tasks like listing directory contents, creating directories, and searching for files more straightforward.

## 02 - Traffic data as image and videos

**Summary:** In this lesson, we'll learn how to work with image and video data for object detection. We'll explore the specific traffic dataset for this project. The focus will be on how video data can be converted to images, understanding bounding boxes for object classification, and using XML annotations to represent those bounding boxes.

**Objectives:**
Load and organize the project dataset, separating images and their corresponding XML annotations.
Extract frames from a video at regular intervals.
Parse XML annotations.
Visualize bounding boxes on image data.

**New Terms:**
Bounding boxes
Frame rate
XML

## 03 - Video Object Detection with YOLO

**Summary:** In this lesson, we won't just classify images but we'll take it a step further by detecting objects within them. We'll use a popular object detection model called YOLO (You Only Look Once).

**Objectives:**
* Detect objects in an image using the YOLO model
* Parse the results from running the YOLO model
* Display the resulting bounding boxes from running the YOLO model
* Detect objects from a variety of sources, including videos and images stored in directories
* Detect objects from a video source

**New Terms:** - Object detection - YOLO - Bounding boxes - Normalized coordinates

## 04 - Training YOLO for Custom Classes

**Summary:** We will use transfer learning to fine-tune a pre-trained YOLO model on the object classes that we care about. This requires us to transform the XML-formatted bounding boxes into a new format that the YOLO model requires. With these transformed labels, we can run a training loop on the YOLO model. After training, we'll be able to detect our object classes in the video frames.

**Objectives:** - Convert bounding boxes to a new representation - Assemble files into the desired directory structure - Cleanly handle malformed data - Fine-tune a model to detect new classes - Detect these new classes in images

**New Terms:** - YAML

## 05 - Data Augmentation

**Summary:** We will explore data augmentation, as it relates to object detection tasks. We start by looking at the data being loaded by a trained YOLO model. This demonstrates that model is trained on augmented data, transformed from the the original images. We then use the Torchvision transforms to generate similar augmented data ourselves.

**Objectives:**
Explore the data loaded for training in the YOLO model
Observe augmented training data in YOLO
Use Torchvision transforms for data augmentation
See how bounding boxes need to transform along with images
Compose several augmentation techniques together

**New Terms:**
Data augmentation