# SKIPSI-Foreign-Object-Detection-on-Conveyor-Belts-
Documentation from Skirpsi


This study aims to develop an automated object detection system based on deep 
learning using the YOLOv11n algorithm to identify foreign objects on coal 
conveyor belts, considering that manual methods have limitations in accuracy and 
consistency. The dataset used is the DsCGF subset Anhui–Guobei productive state, 
which presents complex visual conditions. The research stages include data 
preprocessing (label conversion, image enhancement, data cleaning, and dataset 
balancing) and model training with various parameter configurations. The results 
show that the best model is achieved with a learning rate of 1e-3, batch size of 64, 
and 150 epochs, achieving a performance of mAP@50 of 0.962 and mAP@50–95 
of 0.746 on the validation data. On the test data, the model achieves a precision of 
0.828, recall of 0.783, mAP@50 of 0.836, and mAP@50–95 of 0.628, indicating 
good generalization capability. Furthermore, the application of image 
enhancement significantly improves detection performance, and the resulting 
model has low computational complexity and fast inference time, making it suitable 
for real-time implementation based on edge computing to support quality control 
processes in the mining industry.
