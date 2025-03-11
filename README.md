Curve and Lane Detection and Traffic Signs:

This project focuses on developing a computer vision-based system to detect road lanes, curves, and traffic signs in real-time using OpenCV. The system enhances autonomous driving by accurately identifying road elements under various conditions, including poor lighting, occlusions, and faded markings.

Key Features:
Lane and Curve Detection: Uses Canny edge detection, region-of-interest masking, and Hough Line Transform for robust lane identification.
Traffic Sign Recognition: Implements Haar cascades or a YOLO-based model for detection, with classification using a trained machine learning model (e.g., MobileNet or ResNet).
Dataset Utilization: Employs the TuSimple/KITTI dataset for lane detection and the German Traffic Sign Dataset for sign recognition.
Performance Metrics: Evaluates accuracy with IoU for lane detection and precision/recall for traffic sign recognition, ensuring real-time efficiency (<30ms per frame).
Developed by Begad Tamim & Mohamed Abdelrahim, this project demonstrates how computer vision can contribute to safer transportation systems.
