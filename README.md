# car_plate_detection-with-ocr
The scope of this project includes the development of a license plate detection and OCR system that can process images of vehicles to extract license plate information.
The system will be developed using state-of-the-art computer vision and deep learning techniques.

[Explore Our Presentation](https://www.canva.com/design/DAFjlslyD7M/LLkH2MFOxmLYpRl1Znhwrg/edit?utm_content=DAFjlslyD7M&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

---
# DataSet

This dataset contains 433 images with bounding box annotations of the car license plates within the image.<br>
Our goal here is to train a convolutional neural network capable of locating licenses plate on new images,<br>
And then by using OCR Module will recognize the characters on the license plate and convert them into machine-readable text.<br>

-[Access the data by clicking on](https://drive.google.com/drive/folders/1wxxXEYyoDbg18ij4Do9PZG6u6PqQN77p)

---
# 


# Getting Started
Clone the repository to your local machine to start exploring and contributing to the project:<br>
git clone - 'https://github.com/yasserkh2/car_plate_detection-with-ocr'

---
# Model
This is the Pre-trained CNN Model [VGG-16] used to detect the license plate ,<br>
And 'easyocr'recognize the characters on the license plate and convert them into machine-readable text.<br>
[Take a peek and see what we've done](https://drive.google.com/drive/folders/1dxh9T0tlb6gyFb-euP2FWn4-J082ac4S)

---
# Deployment

Using `Flask` a modern web framework for building APIs in Python, to implement the real-time processing and user interface.<br>
We utilized this framework to implement the real-time processing and user interface, to display the image and first recognize the image is car or not and if the car the will extract the text from the license plate.<br>
-- 'https://drive.google.com/file/d/1WuuPymvLY7R5ACUYWnFOLXF2FcuFel2F/view' The video explains the step-by-step process of deploying the system, including how to display the image and how to first recognize whether the image is a car or not.<br>
Additionally, the video shows how the system can extract the text from the license plate if the image is of a car.<br>

---
# License
  This project is licensed under the GNU General Public License v3.0.
  
---
# Authors

[Yasser Bassem Khira](https://github.com/yasserkh2)<br>
[Rana Mohamed Awad](https://github.com/RanaAwadd)<br>
