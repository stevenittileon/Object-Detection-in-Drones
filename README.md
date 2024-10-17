# Object-Detection-in-Drones

The project was developed as part of a Summer Internship Program at NIT Calicut, with a focus on leveraging the capabilities of drones for innovative agricultural solutions. This project involved training the YOLOv4 model on custom datasets and integrating it into a pipeline for drone footage analysis.

## Project Overview

This project focuses on developing an **Object Detection system for drones using PyTorch and YOLOv5.** The system is designed to detect and classify various objects in real-time from aerial drone footage, with an accuracy of **80%.** The object detection model can be utilized in various applications such as agricultural monitoring, search and rescue missions, surveillance, and environmental studies.

## Key Features

* **Model Framework:** YOLOv4 (You Only Look Once) using PyTorch and Python for implementation.

* **Real-time Detection:** The model is designed for real-time object detection in drone video feeds.

* **Custom Dataset:** The model was trained on a custom dataset tailored for agricultural and outdoor environments.

* **High Performance:** Achieved an object detection accuracy of 80% after extensive training and testing.


## Technologies Used

* **Python:** Main programming language for implementing and training the model.

* **PyTorch:** Deep learning framework used to build, train, and fine-tune the YOLOv4 model.

* **YOLOv5:** State-of-the-art object detection algorithm providing fast and accurate results.

* **OpenCV:** Used for pre-processing drone footage and integrating the object detection system with video inputs.


## Model Architecture

The model is based on YOLOv5, a one-stage object detection algorithm known for its speed and efficiency. Ultralytics YOLOv5 is renowned for its high-speed and high-accuracy object detection capabilities. Built on PyTorch, it is versatile and user-friendly, making it suitable for various computer vision projects. Key features include real-time inference, support for multiple training tricks like Test-Time Augmentation (TTA) and Model Ensembling. It divides the image into a grid and predicts bounding boxes and class probabilities for each grid cell, enabling quick and accurate object detection.


## Dataset and Training

A custom dataset was curated, consisting of images captured from drone footage in agricultural settings. The dataset was manually annotated with bounding boxes for various object classes, including crops, equipment, animals, and obstacles. Main focus was on monkey, pest and mango detection systems.

**Dataset size:** ~2,000 images

**Training duration:** 3-4 hours (on GPU)



## Results

After multiple iterations of training and fine-tuning, the model achieved the following results:

**Accuracy: 80%**

**Precision: 78%**

**Recall: 76%**


## Future Work

* **Model Optimization:** Further optimize the model for higher accuracy and lower latency on embedded systems.

* **Extended Dataset:** Increase the size of the dataset for better generalization to different environments.

* **Advanced Features:** Add object tracking capabilities to monitor detected objects across video frames.


## Contributors

**Team Members: Steven Itti Leon, Ashna Shanavas, K.M.S.S Manaswini, Kollappagari Prathap**

Institution: National Institute of Technology, Calicut


## License

This project is licensed under the MIT License. See the LICENSE file for details.


---

Feel free to reach out for any questions or collaboration opportunities!
