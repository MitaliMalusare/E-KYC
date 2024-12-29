# E-KYC using Computer Vision (OpenCV, DeepFace, OCR)

## Overview

The E-KYC web application automates the Know Your Customer (KYC) process by leveraging advanced techniques in Computer Vision, Natural Language Processing (NLP), and Deep Learning. Users can upload their Aadhar or PAN card along with a photograph, enabling the system to extract face data and verify it against the provided photograph for authentication.

## Features

- **Face Verification**: Utilizes Haarcascade for face detection to extract and match faces from the uploaded ID card. Successful verification allows further operations; otherwise, an error is triggered.

- **Optical Character Recognition (OCR)**: Employs to extract text from the ID card upon successful face verification, based on a pre-configured threshold.

- **Database Interaction**: Checks for existing records in the database before inserting new data. If the user is already registered, no new entry is made, and existing data is returned.

- **Face Embeddings**: Utilizes FaceNet via DeepFace to extract face embeddings, which are then stored in the database.

## Technologies Used

- **Computer Vision**: For face detection and verification.

- **Convolutional Neural Networks (CNNs)**: For image processing tasks.
  
- **PaddleOCR & Keras OCR**: For text extraction (OCR).
  
- **DeepFace**: For generating face embeddings.

- **Haarcascade**: For detecting faces in images.

![image](https://github.com/user-attachments/assets/cb77b0ed-3112-454b-a38b-eef403883170)
