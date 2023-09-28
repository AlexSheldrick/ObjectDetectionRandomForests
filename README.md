# Obect Detection with OpenCV

This capstone project is a key component of the "Tracking and Detection in Computer Vision" course at TU-Munich, taught by Dr. Slobodan Ilic. It offers a focused exploration into practical and theoretical aspects of computer vision, emphasizing object detection using Random Forests.

> By the end of the course, participants will have hands-on experience and a deep understanding of object detection using Random Forests, ready for advanced studies and practical applications in computer vision.

## Task 1: Image Processing and HOG Descriptor

We start with OpenCV for C++, learning about basic image processing and extracting Histogram of Oriented Gradients (HOG) descriptors from images using the built-in HOGDescriptor class.

## Task 2: Object Classification

Next, we implement object classification using Binary Decision Trees and Random Forests with OpenCV’s cv::ml::DTrees class. We create, train, and predict classes, and then extend this knowledge to develop a Random Forest class, learning the ‘create’, ‘train’, and ‘predict’ methods.

This task especially highlighted the advantages of ensemble learning and the importance of hyper parameter tuning.

## Task 3: Object Detection

We apply Random Forests for object detection, utilizing a dataset of diverse objects and backgrounds. Because we are dealing with a small dataset, we take advantage of various image augmentations that should improve accuracy such as rotations, flips and color manipulation. The resulting training procedure achieves enhanced model training and more precise object detection.

![TDCV-HW2](https://github.com/AlexSheldrick/ObjectDetectionRandomForests/assets/59337109/6c09e70f-5f42-4b45-943a-218a2d8b2caa)
