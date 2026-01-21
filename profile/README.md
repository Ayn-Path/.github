<p align ="center">
<img width="400" alt="AynPath" src="https://github.com/user-attachments/assets/b7844e69-fa04-40df-aa6a-7ca3756b21f4" />
</p>

## Overview

Navigating inside large buildings is often difficult for people with disabilities, especially those who are blind or have low vision. Most navigation tools today are designed for outdoor use and depend on GPS, which is unreliable indoors because of weak satellite signals. This makes it challenging to move through complex spaces such as campuses, shopping malls, or office buildings. Existing assistive apps usually focus on one specific feature, like detecting objects, reading text aloud, or guiding someone across a street. To get the full navigation experience, users often have to switch between several different apps, which can be inconvenient and overwhelming.

**AynPath** is my Final Year Project (FYP), developed to bring these needs together in a single application. By combining artificial intelligence and augmented reality, the system offers accurate indoor localization, detects obstacles commonly found in buildings, and provides real-time guidance. Directions are delivered through clear audio cues, gentle haptic feedback, and AR-based visual arrows. For this project, the implementation is focused on **Block A, Level 1 of KICT IIUM**, serving as the test environment for indoor navigation. The goal of AynPath is to give blind and visually impaired people more independence and confidence when moving through indoor environments, making navigation safer, smoother, and easier.

## Diagram:

1. **Use Case Diagram**
<p align="center">
  <img width="339" height="711" alt="Use_Case_Diagram" src="https://github.com/user-attachments/assets/290b5fcb-7330-483a-a4a8-8495d23016e6" />
</p>

* **Scan Environment**: Initiates the system by performing ORB feature detection to recognize virtual markers or detect the user’s location within the indoor environment using a custom VPS.
  
* **Select Destination**: Allows the user to choose their intended destination within the predefined area of the KICT building.
  
* **AR-Based Navigation**: Represents the primary navigation process by displaying virtual arrows as directional guidance toward the selected destination.
  
* **Receive Audio Guidance**: Provides real-time auditory instructions during navigation to assist the user in following the correct path.
  
* **Get Obstacle Alerts**: Notifies the user of any obstacles along the path to ensure safe and accurate navigation.

2. **Flowchart Diagram**

The Activity Diagram below illustrates the main processes in the Ayn-Path system, from scanning the environment to reaching the destination.
<p align="center">
  <img width="339" height="711" alt="Activity_Diagram" src="https://github.com/user-attachments/assets/82553bfe-d313-4ace-8789-91993a1c0601" />
</p>

## Repositories

| Repository | Description |
|------------|-------------|
|[aynpath-app](https://github.com/Ayn-Path/aynpath-app)| It contains the full user interface and functional modules, integrating localization, obstacle detection, audio guidance, haptic feedback, and AR visual arrows.|
|[aynpath-unity](https://github.com/Ayn-Path/aynpath-unity)|Unity is used to render AR navigation by displaying waypoints and paths in the real world and is integrated with Flutter rather than acting as a standalone app.|
|[aynpath-object_detection](https://github.com/Ayn-Path/aynpath-object-detection)| Object detection module powered by MobileNetV2 (TensorFlow Lite). Includes a pretrained model based on the COCO dataset, optimized for detecting common indoor obstacles.|
|[aynpath-datasets](https://github.com/Ayn-Path/aynpath-datasets) | Training and testing datasets for obstacle detection and indoor feature recognition. Includes annotated images, extracted ORB features, and the code for extracting them.|
|[aynpath-server](https://github.com/Ayn-Path/aynpath-server/tree/main)| It contains the ORB (Oriented FAST and Rotated BRIEF) feature processing server.|

## Tools Used
* Flutter
* Unity
* Python

## Video Demonstration

## Acknowledgements
**Supervised** by [Dr. Nurazlin binti Zainal Azmi](https://www.iium.edu.my/directory/show/U0hiM2pjSTQrQkkvdnI2N1BGSlJQUT09)
