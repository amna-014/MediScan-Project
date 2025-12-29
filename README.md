# MediScan AI: Smart Healthcare Inventory System

> **A Digital Transformation (Industry 5.0) Project for Real-Time Medical Supply Recognition.**

[![Platform](https://img.shields.io/badge/Platform-Android-green)]()
[![AI Model](https://img.shields.io/badge/AI-YOLOv11-blue)]()
[![Accuracy](https://img.shields.io/badge/mAP-97.1%25-brightgreen)]()

## Project Overview
**MediScan AI** is a mobile IoT application designed to assist elderly patients and visually impaired individuals in identifying essential medical supplies. By leveraging **Cloud Artificial Intelligence** and **Computer Vision**, the app instantly recognizes pharmaceutical packaging and medical devices, acting as a "Cognitive Prosthetic" for home healthcare.

This project was developed as a final year capstone for the **Design, Technology, & Innovation (DTI)** course, focusing on digitizing manual inventory processes.

## Key Features
* **Real-Time Detection:** Instantly identifies objects with <1 second latency.
* **Intent-Based Architecture:** Engineered a secure bridge between the Android UI and the Chrome WebKit engine to bypass camera hardware restrictions.
* **High Precision:** Achieved **99.3% Precision** on local Pakistani medicine brands.
* **Accessibility First:** Designed with a "Safety Buffer" interface to prevent accidental data usage and simplify the UX for non-technical users.

## Tech Stack
* **Frontend:** MIT App Inventor (Android)
* **Backend/AI:** Roboflow Cloud Inference Engine
* **Model Architecture:** YOLOv11 (Single-Stage Object Detector)
* **Dataset:** Custom-curated dataset of 119 images (Calpol, Saniplast, Thermometers)

## Performance Metrics
The model was trained for 300 epochs using Transfer Learning (COCO Checkpoints).
* **Mean Average Precision (mAP):** 97.1%
* **Precision:** 99.3%
* **Recall:** 97.0%

## Screenshots & Architecture
| User Interface | Backend Logic | Detection Result |
|:---:|:---:|:---:|
| ![UI](https://github.com/amna-014/MediScan-Project/blob/main/20943.jpg?raw=true) | ![Backend](https://github.com/amna-014/MediScan-Project/blob/main/Screenshot%20(131).png?raw=true) | ![Detection](https://github.com/amna-014/MediScan-Project/blob/main/Screenshot%20(127).png?raw=true) |
| *Clean Material Design UI* | *ActivityStarter Intent Blocks* | *Performance Metrics (mAP 97%)* |

> **Note:** Ideally, replace the 3rd image above with a screenshot of your app detecting the Saniplast box!

## How to Test
1.  Download the `MediScan.apk` file from this repository.
2.  Install it on any Android device (Android 10+ recommended).
3.  Click **"Start Medical Scanner"**.
4.  Point the camera at:
    * **Panadol/Calpol Syrup**
    * **Saniplast Box**
    * **Digital Thermometer**

## Development Team
* **Amna Yousuf** (2022F-BBM-012)
* **Shahmeer Hussain** (2022F-BBM-014)
* **Sabeen Ansari** (2022F-BBM-035)

---
*© 2025 MediScan Project. Built for the Dept. of Biomedical Engineering.*
