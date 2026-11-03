1. Project Overview
This repository contains the implementation and documentation for the
CCA 3 Computer Vision practical assignment. The project demonstrates
image restoration, image segmentation, feature extraction and matching,
object detection, and video motion estimation using Python.

The experiments are implemented primarily in the Jupyter Notebook:

My_Computer_Vision_Project.ipynb
2. Objectives
- Add Gaussian and salt-and-pepper noise to an image and restore it
  using Gaussian and median filters.
- Evaluate image restoration using PSNR and SSIM.
- Apply global and adaptive thresholding.
- Perform erosion, dilation, opening and closing.
- Detect edges using the Canny edge detector.
- Perform marker-based image segmentation using Watershed.
- Extract and visualise Histogram of Oriented Gradients (HOG)
  features.
- Detect SIFT keypoints and descriptors and match features between
  photographs.
- Compare SIFT matching before and after a 30-degree image rotation.
- Perform face detection using the Haar Cascade (Viola--Jones) method.
- Perform object detection using the pretrained YOLO11n model.
- Estimate video motion using frame differencing, MOG2 background
  subtraction and Lucas--Kanade optical flow.
3. Technologies Used
  Technology                          Purpose
  Python                              Main programming language

  Jupyter Notebook                    Writing and executing experiments

  OpenCV                              Image processing, feature
detection, object detection and
video analysis

  NumPy                               Numerical operations and image
arrays

  Matplotlib                          Displaying and saving visual
results

  scikit-image                        HOG feature extraction and
PSNR/SSIM metrics
Ultralytics                         Running the pretrained YOLO11n
model
4. Repository Structure
Computer-Vision-Assignment/
│
├── My_Computer_Vision_Project.ipynb
├── yolo11n.pt
├── README.md
├── requirements.txt
│
├── input/
│   ├── myphoto (2).jpeg
│   ├── myphoto2.jpeg
│   ├── myphoto3.jpg
│   └── my_recorded_video.mp4       # Add your own recorded video for final Task 4
│
├── outputs/
│   ├── Image restoration results
│   ├── Segmentation results
│   ├── HOG and SIFT visualisations
│   ├── Haar Cascade and YOLO detections
│   └── Motion estimation results
│
└── docs/
    └── CCA3_Computer_Vision_Report.docx
Note: The exact output filenames may differ depending on the notebook
execution. The outputs/ directory contains selected generated result
images.
5. Tasks Implemented
Task 1 -- Image Restoration and Segmentation
This task applies image processing methods to the primary input
photograph.
- Gaussian noise and salt-and-pepper noise addition.
- Gaussian filtering and median filtering.
- Image quality evaluation using PSNR and SSIM.
- Global binary thresholding and adaptive thresholding.
- Morphological operations: erosion, dilation, opening and closing.
- Canny edge detection.
- Marker-based Watershed segmentation.
Task 2 -- Feature Extraction and Image Matching
This task extracts visual features and compares photographs.
- Histogram of Oriented Gradients (HOG) feature extraction and
  visualisation.
- SIFT keypoint and descriptor extraction.
- Brute Force feature matching with Lowe's ratio test.
- Feature matching after rotating the primary photograph by 30
  degrees.
Task 3 -- Object Recognition
This task compares two pretrained object/face detection approaches.
- Face detection using the Haar Cascade classifier based on the
  Viola--Jones approach.
- General object detection using the pretrained YOLO11n model.
- Visualisation of detected bounding boxes, class labels and
  confidence scores.
Task 4 -- Video Motion Estimation
This task analyses movement between video frames.
- Consecutive frame extraction.
- Frame differencing and threshold-based motion mask.
- GMM-based background subtraction using MOG2.
- Sparse optical flow using the Lucas--Kanade method.
Important: The development notebook previously used a downloaded
sample video. The assignment requires an original, unedited,
self-recorded video of approximately 15--30 seconds. Before final
submission, add your own video as input/my_recorded_video.mp4, update
the video path in the notebook, rerun all Task 4 cells, and replace the
corresponding output images and report observations. Do not present the
downloaded sample as your own recording.
6. Setup and Installation
Prerequisites
- Python 3.x
- Anaconda or another Python environment
- Jupyter Notebook
- Git (optional, for cloning the repository)
Clone the repository
git clone https://github.com/theyashgite/Computer-Vision-Assignment-.git
cd Computer-Vision-Assignment-
Install dependencies
pip install -r requirements.txt
If Jupyter Notebook is not installed:
pip install notebook
Launch the notebook
jupyter notebook
Open My_Computer_Vision_Project.ipynb and execute the cells in order.
7. Input Files and Model Weights
- Place the three project photographs in the input/ directory.
- Keep the image filenames consistent with the paths used in the
  notebook.
- Keep yolo11n.pt in the repository root if the notebook loads the
  model using YOLO('yolo11n.pt').
- Add the required self-recorded video to input/ and update the
  notebook video path before the final Task 4 run.
8. Results and Documentation
The notebook generates visual results for the four tasks. Selected
result images are stored in outputs/.

The technical report is available at:

docs/CCA3_Computer_Vision_Report.docx

The report describes the methods, parameters, outputs, comparisons,
observations and limitations. Update the Task 4 figures and observations
after processing the original self-recorded video.
9. Submission Links
- GitHub Repository:
  https://github.com/theyashgite/Computer-Vision-Assignment-
- Google Drive Submission Folder:
  https://drive.google.com/drive/folders/1eMQZMjgl1opN6KTvQXa1bJAkjKWb5S2R
- Project Explanation Video (5--8 minutes): Add the final Google
  Drive video link after recording and uploading.
10. Final Submission Checklist
- [ ] Run the notebook successfully from beginning to end.
- [ ] Record an original 15--30 second video.
- [ ] Rerun Task 4 using the self-recorded video.
- [ ] Replace the provisional Task 4 results and observations in the
  technical report.
- [ ] Upload the updated notebook, report and selected outputs to
  GitHub.
- [ ] Upload the original input files and final deliverables to the
  Google Drive folder.
- [ ] Record and upload the 5--8 minute project explanation video.
- [ ] Verify that the faculty members have access to the Google Drive
  folder.
11. Faculty Access
Share the Google Drive submission folder with the faculty email
addresses specified in the assignment:
- rahul.inchal.inchal24@gmail.com
- rahul.inchal.vf@mitwpu.edu.in
12. References
- OpenCV Documentation: https://docs.opencv.org/
- scikit-image Documentation: https://scikit-image.org/docs/
- Ultralytics Documentation: https://docs.ultralytics.com/
- Python Documentation: https://docs.python.org/3/
