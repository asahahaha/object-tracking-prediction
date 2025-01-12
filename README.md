# Research Project: Frame Prediction for Aerial Objects
```
* Team Members: Jonathan, Rongge, Keyu
* Related Course: COMP 558 Fundamentals of Computer Vision
* Instructor: Kaleem Siddiqi
```

All codes written in MatLab. Click [here](frame_prediction_report.pdf) to see the report.

<img src="preview.png" alt="" width="300"/>


## Abstract
Next frame video prediction is an active research topic with extensive applications in many areas, such as autonomous driving and robotic decision-making. Recent developments in deep learning have allowed for the prediction of future events by analyzing historical frame data. In this project, we focused on predicting the paths of aerial objects using a stationary camera and classical com- puter vision algorithms. We implemented a sequence of methods including Farneback optical flow, Meanshift object tracking, RANSAC with least squares, Canny edge detection and median filtering for background generation. To demonstrate our results, we will present an example of a recorded video with the predicted frames added to the end. We found that the classical computer vision algorithms were effective for detecting the object, tracking it, predicting its path, copying it, and pasting it onto future frames. However, our implementation of these algorithms was not very robust and would only work with particular videos in which the object is very distinct from the background. Furthermore, our algorithms made a number of assumptions about the object, such as no rotation or movement along the z-axis. Nevertheless, given the assumptions we made, we were successful at predicting future frames, proving that classical computer vision algorithms are useful and effective for frame prediction.
* Keywords: frame prediction, video sequence, Farneback optical flow, object tracking, RANSAC, object extraction, background modelling.
