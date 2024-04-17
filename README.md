# Smart-Beach_phase-3_Classification_-_objectCount
This repository implements a system for predicting and counting people on a beach scene using YOLOv5 and Faster R-CNN models. It divides the scene into zones, counts objects in each zone, and evaluates model performance.

#Features
Object detection using YOLOv5 and Faster R-CNN.
Zone-based objetcs counting and visualization.
Performance evaluation with precision, recall, and accuracy metrics.

#Usage
Clone the repository to your local machine.
Ensure all dependencies are installed (requirements.txt).
Add test images to the test-data/ directory.
Run the 'Zone_Based_Image_Classification_and_Object_Count' script.
View processed images and evaluation metrics in the test-data/op/ directory.

#Dependencies
PyTorch
NumPy
Pillow
Matplotlib
torchvision
