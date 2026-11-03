Project Overview
This project demonstrates the practical application of fundamental Computer Vision techniques. Computer Vision is a field of Artificial Intelligence that enables computers to interpret and understand visual information such as images and videos.

The project explores how images can be enhanced, how important visual features can be identified and matched, how objects and faces can be detected, and how movement can be analysed in video.
Objectives
- Understand and apply basic image processing techniques.
- Reduce noise and improve image quality.
- Extract useful visual features from images.
- Identify similarities between different images.
- Detect faces and objects in images.
- Analyse movement and track objects across video frames.
- Understand the practical use of computer vision in real-world applications.
Main Components of the Project
1. Image Processing and Enhancement
This component focuses on improving and analysing digital images. Different types of noise are added to images to understand how image quality is affected. Filtering techniques are then applied to reduce the noise and restore image quality.

The project also explores thresholding to separate foreground regions from backgrounds, morphological operations to modify image regions, edge detection to identify object boundaries, and watershed segmentation to separate objects.
2. Feature Extraction and Matching
Images contain important visual information such as edges, corners, shapes, and patterns. This component extracts these features so that images can be analysed and compared.

HOG (Histogram of Oriented Gradients) is used to represent image structure, while SIFT (Scale-Invariant Feature Transform) identifies distinctive keypoints and descriptors. Feature matching is used to find similarities between images, including when an image is rotated.
3. Face and Object Detection
This component demonstrates how computer vision systems identify faces and objects in images.

A Haar Cascade classifier is used for face detection, while a pretrained YOLO model is used for object detection. The detected objects are highlighted with bounding boxes, labels, and confidence scores. The results help demonstrate the differences between traditional detection methods and deep-learning-based object detection.
4. Motion Detection and Optical Flow
This component focuses on understanding movement in video. Consecutive video frames are analysed to identify changes and detect moving regions.

Frame differencing and background subtraction are used to separate moving objects from the background. Lucas–Kanade optical flow is used to track selected feature points and estimate their movement between frames.
Applications of Computer Vision
The techniques demonstrated in this project are used in many real-world applications, including:
- Security and surveillance: Monitoring scenes and detecting people or objects.
- Autonomous vehicles: Identifying vehicles, pedestrians, and road features.
- Healthcare: Supporting the analysis of medical images.
- Robotics: Helping robots recognise objects and understand their surroundings.
- Video analytics: Detecting movement and tracking objects.
- Image search and recognition: Finding and comparing visually similar images.
Conclusion
This project provides practical exposure to four important areas of Computer Vision: image processing, feature extraction and matching, object detection, and motion analysis.

By implementing and observing these techniques, the project demonstrates how computers can process visual data, identify meaningful information, recognise objects, and analyse movement. It also highlights how different computer vision methods are useful for solving real-world problems.
